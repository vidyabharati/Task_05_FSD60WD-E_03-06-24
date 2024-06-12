# Task_05_FSD60WD-E_03-06-24
Task_05_FSD60WD-E_03-06-24-ES5 vs ES6

////Question 1) For the given JSON iterate over all for loops (for, for in, for of, forEach)

//for in loop
var obj = [
  { person: "Name", age: "2", company: "Guvi" },
  { person: "Name", age: "3", company: "Guvi Geek" },
  { person: "Name", age: "4", company: "Guvi Geek Network" },
];
for (var index in obj) {
  user = obj[index];
  console.log(`Name: ${user.person};
  Age: ${user.age};
  Company: ${user.company}`);
}

// for of
var obj = [
  { person: "Name", age: "2", company: "Guvi" },
  { person: "Name", age: "3", company: "Guvi Geek" },
  { person: "Name", age: "4", company: "Guvi Geek Network" },
];
for (var key of obj) {
  console.log(`
   Name: ${key.person};
  Age: ${key.age};
  Company: ${key.company}`);
}

// forEach
var obj = [
  { person: "Name", age: "2", company: "Guvi" },
  { person: "Name", age: "3", company: "Guvi Geek" },
  { person: "Name", age: "4", company: "Guvi Geek Network" },
];
obj.forEach((user) => {
  console.log(`
  Name: ${user.person};
  Age: ${user.age};
  Company: ${user.company}`);
});



////Question2) Create your own resume data in JSON format
answer:
//Resume:

let data = [
  {
    basics: {
      name: "Vidyabharati H Kodihal",
      objective:
        "I am a young professional with an interest for emerging new web technologies and with experience in the digital industry. I am looking for a role that will challenge and broaden my coding knowledge, whilst learning new technologies and languages. I am particularly keen to thrive in a creative environment.",
      email: "kodihalv@gmail.com",
      education: {
        graduation: "B.E Electrical and Electronics Engineering (EEE)",
        college: "V.V.P.I.E.T, Solapur",
        aggregatePercentage: "65.83%",
        academicAchievement:
          "Stood FIRST in Solapur University Examination 2013-14",
      },
      location: {
        city: "Pune",
        countryCode: "IN",
      },
    },

    work: [
      {
        highlights: ["Mathematics and Science Lecturer "],

        company: "Survase Pvt.ITI",
        Email: "survase_itc@yahoo.com",
        position: "Lecturer",
        startDate: "2015-06-07",
        endDate: "2016-07-09",
      },
      {
        highlights: ["Science Teacher"],

        company: "Brijmohan Phofaliya’s Ideal English Medium School.",
        position: "Teacher",
        startDate: "2018-06-15",
        endDate: "2021-07-07",
      },
    ],
    interests: [
      {
        name: "Badminton",
      },
      {
        name: "Self Study",
      },
    ],
    personalMemoranda: [
      {
        dateOfBirth: "1993-04-11",
        gender: "Female",
      },
      {
        declaration:
          "The above information provided is true to best of my knowledge.",
      },
    ],
  },
];
