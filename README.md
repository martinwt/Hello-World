# Hello-World
I have no idea what I'm doing
What am I supposed to do with this?


var combos = function(arr) {
    var combinations = [];
       for (var i = 0; i<arr.length-1; i++) {
         for (var j = i+1; j<arr.length; j++) {
           combinations.push([arr[i],arr[j]]);
         }
       }
    console.log(combinations);
};
