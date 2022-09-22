# TASK-1.2.1
def is_prime (num):
 check=True
 i=2;
 while i*i<=num:
     if(num%i==0):
         check=False
         break
     i+=1

 if(check and num!=1):
    return(str(num)+" is a Prime Number")
 else:
     return(str(num)+" is not a Prime Number")
is_prime(12)
