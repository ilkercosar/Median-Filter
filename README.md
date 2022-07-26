# Median Filter
Two input single output Median filter with queque algorithm.

# Information 
vector x and y n elements and window size k
vector t is arithmetic mean x-y

output vector is w with n - k +1 elements

y[i] is the median of  t[i], t[i+1], ..., t[i+k−1].

# Algorithm

--> x[i]          
--> y[i]                  
                                    
--> t[i] = (x[i] + y[i]) / 2  
                                      
-- is buffer equal to 3   

--> Sorting to buffer //  buffer[2], buffer[1], buffer[0] || buffer[2] = min value, buffer[0] = maks value, buffer[1] = median value 

--> return Median value


