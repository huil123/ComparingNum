# ComparingNum
def Compating_Num(a_list):
    sum_of_list = 0
    for i in a_list:
      sum_of_list += i 
    for n in range (length(a_list)):
       for i in range (n, length(a_list)):
         if a_list[n] * a_list[i] > sum_of_list:
           print("{ "+a_list[n] + " , " + a_list[i] + "}")
