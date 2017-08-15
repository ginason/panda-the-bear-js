#1
panda = document.querySelector("img");
panda.src = file:///Users/ginason/Desktop/week9/Aug15/panda-the-bear-js/images/self-portrait-snowbg.jpg

#2
var headText = document.querySelector("h1");
headText.innerText = "Gina";

#3
var emp = document.querySelectorAll(".info-title");
emp = emp[1];
emp.innerText = "My History";

#4
var body = document.querySelector('body');
body.style.background = "red";

#5
var highlightClass = document.querySelector(".highlight");
highlightClass.style.background = "pink";

#6
var fontFamily = document.querySelector("h1");
fontFamily.style.fontFamily = "momospace";

#7
var icons = document.querySelectorAll(".action-icon-bg");
for(i=0; i < icons.length; i++){
  icons[i].style.background = "pink";
}


#8
var namePlaceHolder = document.querySelector("input#name");
namePlaceHolder.placeholder = "identify yourself";

#9
var messagePlaceHolder = document.querySelector("textarea#message");
messagePlaceHolder.placeholder = "state your business";

#10
namePlaceHolder.value = "your nemesis";

#11
var emailPlaceHolder = document.querySelector("input#email");
emailPlaceHolder.value = "koalathebear@gmail.com";

#12
var submitButton = document.querySelector("input#submit");
submitButton.value = "En garde!";
#13
submitButton.disabled=true;
#14
var info = document.querySelectorAll("span.bio-info-value");
for(i=0; i<info.length; i++){
  info[i].innerText = "";
}
