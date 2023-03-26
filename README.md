# sorting-and-searching

##selection sort
```cpp
vector<int>selection (vector<int> &arr, int n) {
  for (int i = 0; i < n - 1; i++) {
    int mineleindex = i;
    for (int j = i + 1; j < n; j++) {
      if (arr[j] < arr[mineleindex]) {
        mineleindex = j;
      }
      swap(arr[i], arr[mineleindex]);
    }
  }
  return arr;
}'''

## bubble sort
```cpp
