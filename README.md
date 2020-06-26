1.# Python code to illustrate                                                                                                                                                       
                                                                                                                                                                                   
filter() with lambda()                                                                                                                                                             
li = [5, 7, 22, 97, 54, 62, 77, 23, 73, 61]                                                                                                                                     
                                                                                                                                                                                  
final_list = list(filter(lambda x: (x%2 != 0) , li))                                                                                                                              
                                                                                                                                                                                
print(final_list)                                                                                                                                                                   
                                                                                                                                                                          
python code to illustrate                                                                                                                                                         
map() with lamda()                                                                                                                                                                
to get double of list                                                                                                                                                            
li = [5, 7, 22, 97, 54, 62, 77, 23, 73, 61]                                                                                                                                       
                                                                                                                                                                                
final_list = list(map(lambda x: (x%2 != 0), li))                                                                                                                                  
print(final_list)                                                                                                                                                                                                                                                                                                                                                  
                                                                                                                                                                                
O/P: [5, 7, 97, 77, 23, 73, 61]                                                                                                                                                          [True, True, False, True, False, False, True, True, True, True]

2.                                                                                                                                                                                  def isPrime(x):                                                                                                                                                                  
for n in range(2,x):                                                                                                                                                               
if x%n==0:                                                                                                                                                                         
return False                                                                                                                                                                    
else:                                                                                                                                                                             
return True fltrObj=filter(isPrime, range(2500))                                                                                                                                  
print ("Prime numbers between 1-2500")                                                                                                                                           
                                                                                                                                                                                   
O/P:
Prime numbers between 1-2500

