# saints-stars-V1

Ik had de HTML goed gedaan

Enkel kwam ik er uiteindelijk achter dat mijn website helemaal niet responsive was en ik dus helemaal opnieuw moest beginnen met mijn css

Hier is mijn CSS code, ik ben al verder gegaan met een responsive css in mijn document, volgende keer even netjes bijhouden op github!


@import url('https://fonts.googleapis.com/css2?family=Titillium+Web:ital,wght@0,200;0,300;0,400;0,600;0,700;0,900;1,200;1,300;1,400;1,600;1,700&display=swap');

body {
    font-family: 'Titillium Web', sans-serif;
    color: #333;
    line-height: 1.6;
    padding: 0; margin: 0;
    text-align: center;
}

h1, h2, h3 {
    font-weight: 300;
    margin: .5em;
    line-height: 1.2;
}

p {
    text-align: center;
    margin: .5em;
}

img, video {
    width: 100%;
}

video {
    position: relative;
    z-index: -1;
}

/* Header */


/* logo */
header img {
    position: absolute;
    text-align:center;
    width: 40%;

}

header h1, p{
color: white;
position: absolute;
}

header h1 {
    top: 4em;
    left: 2em;
    font-weight: 600;
    text-transform: uppercase;
}

/* cta */
.button1 {
    background-color: cornflowerblue;
    padding: 0 1em 0;
    border-radius: 1em; 
    position: absolute;
    top: 5.8em;
    left: 8em;
}

/* First timer & holy workouts */
#firsttimer h3 {
    font-weight: 600;
    color: white;
    text-transform: uppercase;
}

#firsttimer h3:first-of-type {
    position: absolute;
    top: 42%;
    left: 35%;
}

#firsttimer h3:last-of-type {
    position: absolute;
    top: 70%;
    left: 15%;
    text-align: center;
}

#firsttimer {
    margin: 3em 0;
    background: black;
}

#firsttimer img {
opacity: .5;
}

/* This is our tribe */

#tribe {
    margin: 3em;
    text-align: center;
}

#tribe p {
    color: black;
}

CODE nr 2 (deze heb ik ook vervangen omdat hij niet responsive genoeg was)

/* even wat standaard css dingetjes */
 
@import url('https://fonts.googleapis.com/css2?family=Titillium+Web:ital,wght@0,200;0,300;0,400;0,600;0,700;0,900;1,200;1,300;1,400;1,600;1,700&display=swap');
 
* {
   box-sizing: border-box;
}
body {
   font-family: 'Titillium Web', sans-serif;
   color: #333;
   line-height: 1.6;
   padding: 0; margin: 0;
   text-align: center;
   width: 100vw;
}
 
h1, h2, h3 {
   font-weight: 300;
   line-height: 1.2;
}
 
p {
   text-align: center;
}
 
img, video {
   width: 100%;
}
 
video {
   position: relative;
   z-index: -1;
}
 
/* Header */
 
header div{
position: absolute;
width: 100vw;
padding: 2em;
}
 
header img {
   margin-top: 10%;
   text-align:center;
   width: 40%;
}
 
header h1 {
font-weight: 600;
text-transform: uppercase;
}
 
header p,h1 {
   color:white;
}
 
/* CTA */
 
.button1 {
   background-color: cornflowerblue;
   border-radius: 1em;
   margin-top: 7%;
}
 
