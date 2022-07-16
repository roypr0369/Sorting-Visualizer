# Sorting-Visualizer
Sorting is very useful concept in a real-life scenario. I have tried to make it visualize it.

>Check the Website here:    
https://sortingvisualizer-new.netlify.app/

# What is Sorting?
In computer science, a sorting algorithm is an algorithm that puts elements of a list into an order. The most frequently used orders are numerical order and lexicographical order, and either ascending or descending.

# Pseudocode of sorting algorithms

> Bubble Sort

```
//n is the size of the array
for(int i = n - 1; i > 0; i--){
  for(int j = 0; j < i; j++){
    if(arr[i] < arr[j]){
      swap arr[i] and arr[j]
    }
  }
}
```

> Selection Sort

```
//n is the size of the array
for(int i = 0; i < n; i++){
  int temp_index = i;
  for(int j = i + 1; j < n; j++){
    if(arr[j] < arr[temp_index]){
      temp_index = j;
    }
  }
  if(i != temp_index){
    swap arr[i] and arr[temp_index]
  }
}
```

> Exchange Sort

```
//n is the size of the array
for(int i = 0; i < n; i++){
  for(int j = i + 1; j < n; j++){
    if(arr[i] < arr[j]){
      swap arr[i] and arr[j]
    }
  }
}
```

>Insertion Sort

```
//n is the size of the array
for(int i = 1; i < n; i++){
  int key = arr[i];
  int j = i - 1;
  while(key < arr[j] && j >= 0){
    arr[j + 1] = arr[j];
    j--;
  }
  arr[j + 1] = key;
}
```

