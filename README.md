# day-three-task

//Iterate for all loops (for, for in, for of, for each)

//for loop

let i;
for(i=0; i<=10; i++){
    console.log(i);
}


//for loop in array
var a = 0;
let list = ["ktm", "royal enfiled", "bullet", "scooty" , "cycle"];
for(a=0; a<list.length; a++){
    console.log(list[a]);
}


//for of loop

let list = ["ktm", "royal enfiled", "bullet", "scooty" , "cycle"];
for(let tam of list){
    console.log(tam);
}




//for in loop 
var object = {
    name: "tamil",
    age: 25,
    bike : "ktm"
}

for(let user in object){
    console.log(`key is ${user} value is ${object[user]}`); //Template literal
}


/// for rach()

let list = ["ktm", "royal enfiled", "bullet", "scooty" , "cycle"];
list.forEach((e)=> {
    console.log(e);
});

//JSON

let objectJSON = JSON.stringify(object); //changing object to string
console.log(objectJSON);

let objectrev = JSON.parse(objectJSON);  // changing string to an object
console.log(objectrev);



//2. create your own resume data in JSON Format

var resume = {
    name: "tamilselvan",
    DOB: "17/11/1998",
    age: 23,
    Degree: "B.E computer science",
    percentage: 84,
    programming_languages: "javascript,html,css,react.js",
    prior_work_exp:"1 year"
}

var resumeJSON = JSON.stringify(resume); //changing object to string 
console.log(resumeJSON);

var resumeorg = JSON.parse(resumeJSON);  //chnaging string to an object
console.log(resumeorg) ;
