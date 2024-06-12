# C-DSA

#ARRAY[easy]
--------auto max = find(nums.begin(),nums.end(),max); //to access max element *max as max is iterator
        auto min = min_element(nums.begin(),nums.end()); // same here
        auto maxIdx = find(nums.begin(),nums.end(),*max); // same here
        auto minIdx = find(nums.begin(),nums.end(),*min); // same here

//to check sorted and rotated array
bool isSorted(int arr[], int n) {
  for (int i = 1; i < n; i++) {
    if (arr[i] < arr[i - 1])
      return false;
  }

  return true;
}
        
