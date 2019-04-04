1.
var profileImage = document.querySelector('.profile-image'); profileImage.src = "https://placebear.com/200/300";
iceImage.src
1.
var iceImage = document.querySelector('.portfolio-image img');
"http://bitmakerlabs.github.io/panda-the-bear-js/images/clouds-man.jpg"
iceImage.src = "https://placebear.com/200/300";
"https://placebear.com/200/300"

3.var employment = document.querySelector('div #employment'); var title = employment.querySelector('.info-title'); title.innerText = "Hi";
"Hi"

4.var body = document.body; body.style.backgroundColor = 'orange';

5.var highlight = document.getElementsByClassName("highlight");
for (var i = 0; i < highlight.length; i++) { current = highlight[i]; current.style.color = "red "; }
"red

6.var h1 = document.querySelector('h1'); h1.style.fontFamily = "monospace";

7.var round = document.querySelector('.action-container'); round.style.backgroundColor = "blue";

8.var form = document.querySelector('form'); var input = form.querySelector('#name'); input.placeholder = "identify yourself";

Part 2:
1.var div = document.querySelector('#time-travel'); var title = div.querySelector('.bar-title'); div.removeChild(title)

2.var PikachuImage = document.querySelector('.portfolio-image#right-image img'); var dumpPikachuImage = PikachuImage.cloneNode(true); var PortfolioContainer = document.querySelector('.Portfolio-container'); PortfolioContainer.appendChild(dumpPikachuImage);
