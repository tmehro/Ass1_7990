# Program to remove duplicates from a list

### Define a new function called duplicate
> def Remove(duplicate):
### Create an empty list to store unique numbers
>    final_list = []
### Loop through the list and add to final_list if not found in final_list 
```   
 for num in duplicate:
    if num not in final_list:
       final_list.append(num)
       return final_list
```    
## Call the function and pass values
```
  duplicate = [2, 4, 10, 20, 5, 2, 20, 4]
  print(Remove(duplicate))
``` 
