# javascript-algorithms-and-data-structures-basic-algorithm-scripting-repeat-a-string-repeat-a-string-
javascript-algorithms-and-data-structures/basic-algorithm-scripting/repeat-a-string-repeat-a-string/

Basic Algorithm Scripting: Repeat a String Repeat a String
Repeat a given string str (first argument) for num times (second argument). Return an empty string if num is not a positive number.

Remember to use Read-Search-Ask if you get stuck. Write your own code.
repeatStringNumTimes("*", 3) should return "***".
Passed
repeatStringNumTimes("abc", 3) should return "abcabcabc".
Passed
repeatStringNumTimes("abc", 4) should return "abcabcabcabc".
Passed
repeatStringNumTimes("abc", 1) should return "abc".
Passed
repeatStringNumTimes("*", 8) should return "********".
Passed
repeatStringNumTimes("abc", -2) should return "".
Passed
The built-in repeat()-method should not be used

function repeatStringNumTimes(str, num) {
  // repeat after me
let empty="";
let text=[];
if(num > 0){
  for(let i=0; i < num;  i++){
    text+=str;
  }
return text;
}else{
console.log(text);
return empty;
} 
}
repeatStringNumTimes("abc", -2);
