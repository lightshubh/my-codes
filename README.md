# bubble sort


my_list=[1,2,1,4,7,85,21,0,1,4,6,2,4,7,56]

def bubble_sort(): 
    i=0
    temp=my_list[i]

    for item in range(len(my_list)-1):
        if temp>my_list[i+1]:
            temp=my_list[i]
            my_list[i]=my_list[i+1]
            my_list[i+1]=temp
        elif temp<my_list[i+1]:
            temp=my_list[i+1]
        else:
            temp=my_list[i+1]
            
        
        i += 1  
        
if my_list != my_list.sort():
    bubble_sort()

print(my_list)
