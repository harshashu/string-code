# string-code
program to find the reverse of a string irrespective of the length of the string
function reverse1(str1){

  let r = "";

  for(let i = str1.length-1; i >= 0; i--){

    r += str1[i];

  }

  return r;

}

console.log(reverse1("proverb"))

function reverse2(str2){

  let p = "";

  for(let i = str2.length-1; i >= 0; i--){

    p += str2[i];

  }

  return p;

  

}

console.log(reverse2("ooklomnojkjkjk"))
