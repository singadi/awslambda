import json

def lambda_handler(event, context):
    #var input = 3;
    #return 0;
    return getFibonacci(event.get("item"));
	#return result;
  
def getFibonacci(n):
    if(n == 0):
        return 0
    else:
        if(n == 1):
            return n 
        else:
            if(n > 1):
                return getFibonacci(n-1) + getFibonacci(n-2)
