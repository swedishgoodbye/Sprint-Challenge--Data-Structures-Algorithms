Add your answers to the Algorithms exercises here.


### Exercise 1

+ A: O(n)
+ B: O(n)
+ C: O(3n)
+ D: O(Logn)
+ E: O(4n)
+ F: O(1)
+ G: O(n^2)


### Excercise 2

+ A:

```javascript

function maxAlg(arr){
    let max = -1;
    for (let i = 0; i < arr.length; i++ ){
        for (let l = arr.length - 1; --j){
            if(arr[j] > arr[i] && max < (j-1))
            max = j - i;
        }
    }

    return max;
}

```

### Exercise 3

+ A: The complexity would be O(n^2) because every time you used the sort you would have to double all your work if you didn't have a center pivot.

+ B: The complexity would be O(n log n) since you're dividing your work in half.