html,
body {
  width: 100%;
  height: 100%;
}

body {
  font-family: 'Muli', 'Helvetica', 'Arial', 'sans-serif';
}

a {
  color: #fdcc52;
  transition: all .35s;
}

a:hover, a:focus {
  color: #fcbd20;
}

hr {
  max-width: 100px;
  margin: 25px auto 0;
  border-width: 1px;
  border-color: rgba(34, 34, 34, 0.1);
}

hr.light {
  border-color: white;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Catamaran', 'Helvetica', 'Arial', 'sans-serif';
  font-weight: 200;
  letter-spacing: 1px;
}

p {
  font-size: 18px;
  line-height: 1.5;
  margin-bottom: 20px;
}

section {
  padding: 100px 0;
}

section h2 {
  font-size: 50px;
}

#mainNav {
  border-color: rgba(34, 34, 34, 0.05);
  background-color: white;
  transition: all .35s;
  font-family: 'Catamaran', 'Helvetica', 'Arial', 'sans-serif';
  font-weight: 200;
  letter-spacing: 1px;
}

#mainNav .navbar-brand {
  color: #fdcc52;
  font-family: 'Catamaran', 'Helvetica', 'Arial', 'sans-serif';
  font-weight: 200;
  letter-spacing: 1px;
}

#mainNav .navbar-brand:hover, #mainNav .navbar-brand:focus {
  color: #fcbd20;
}

#mainNav .navbar-toggler {
  font-size: 12px;
  padding: 8px 10px;
  color: #222222;
}

#mainNav .navbar-nav > li > a {
  font-size: 11px;
  font-family: 'Lato', 'Helvetica', 'Arial', 'sans-serif';
  letter-spacing: 2px;
  text-transform: uppercase;
}

#mainNav .navbar-nav > li > a.active {
  color: #fdcc52 !important;
  background-color: transparent;
}

#mainNav .navbar-nav > li > a.active:hover {
  background-color: transparent;
}

#mainNav .navbar-nav > li > a,
#mainNav .navbar-nav > li > a:focus {
  color: #222222;
}

#mainNav .navbar-nav > li > a:hover,
#mainNav .navbar-nav > li > a:focus:hover {
  color: #fdcc52;
}

@media (min-width: 992px) {
  #mainNav {
    border-color: transparent;
    background-color: transparent;
  }
  #mainNav .navbar-brand {
    color: fade(white, 70%);
  }
  #mainNav .navbar-brand:hover, #mainNav .navbar-brand:focus {
    color: white;
  }
  #mainNav .navbar-nav > li > a,
  #mainNav .navbar-nav > li > a:focus {
    color: rgba(255, 255, 255, 0.7);
  }
  #mainNav .navbar-nav > li > a:hover,
  #mainNav .navbar-nav > li > a:focus:hover {
    color: white;
  }
  #mainNav.navbar-shrink {
    border-color: rgba(34, 34, 34, 0.1);
    background-color: white;
  }
  #mainNav.navbar-shrink .navbar-brand {
    color: #222222;
  }
  #mainNav.navbar-shrink .navbar-brand:hover, #mainNav.navbar-shrink .navbar-brand:focus {
    color: #fdcc52;
  }
  #mainNav.navbar-shrink .navbar-nav > li > a,
  #mainNav.navbar-shrink .navbar-nav > li > a:focus {
    color: #222222;
  }
  #mainNav.navbar-shrink .navbar-nav > li > a:hover,
  #mainNav.navbar-shrink .navbar-nav > li > a:focus:hover {
    color: #fdcc52;
  }
}

header.masthead {
  position: relative;
  width: 100%;
  padding-top: 150px;
  padding-bottom: 100px;
  color: white;
  background: url("../img/bg-pattern.png"), #7b4397;
  background: url("../img/bg-pattern.png"), linear-gradient(to left, #7b4397, #dc2430);
}

header.masthead .header-content {
  max-width: 500px;
  margin-bottom: 100px;
  text-align: center;
}

header.masthead .header-content h1 {
  font-size: 30px;
}

header.masthead .device-container {
  max-width: 325px;
  margin-right: auto;
  margin-left: auto;
}

header.masthead .device-container .screen img {
  border-radius: 3px;
}

@media (min-width: 992px) {
  header.masthead {
    height: 100vh;
    min-height: 775px;
    padding-top: 0;
    padding-bottom: 0;
  }
  header.masthead .header-content {
    margin-bottom: 0;
    text-align: left;
  }
  header.masthead .header-content h1 {
    font-size: 50px;
  }
  header.masthead .device-container {
    max-width: 325px;
  }
}

section.download {
  position: relative;
  padding: 150px 0;
}

section.download h2 {
  font-size: 50px;
  margin-top: 0;
}

section.download .badges .badge-link {
  display: block;
  margin-bottom: 25px;
}

section.download .badges .badge-link:last-child {
  margin-bottom: 0;
}

section.download .badges .badge-link img {
  height: 60px;
}

@media (min-width: 768px) {
  section.download .badges .badge-link {
    display: inline-block;
    margin-bottom: 0;
  }
}

@media (min-width: 768px) {
  section.download h2 {
    font-size: 70px;
  }
}

section.features .section-heading {
  margin-bottom: 100px;
}

section.features .section-heading h2 {
  margin-top: 0;
}

section.features .section-heading p {
  margin-bottom: 0;
}

section.features .device-container,
section.features .feature-item {
  max-width: 325px;
  margin: 0 auto;
}

section.features .device-container {
  margin-bottom: 100px;
}

@media (min-width: 992px) {
  section.features .device-container {
    margin-bottom: 0;
  }
}

section.features .feature-item {
  padding-top: 50px;
  padding-bottom: 50px;
  text-align: center;
}

section.features .feature-item h3 {
  font-size: 30px;
}

section.features .feature-item i {
  font-size: 80px;
  display: block;
  margin-bottom: 15px;
  background: linear-gradient(to left, #7b4397, #dc2430);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

section.cta {
  position: relative;
  padding: 250px 0;
  background-image: url("../img/bg-cta.jpg");
  background-position: center;
  background-size: cover;
}

section.cta .cta-content {
  position: relative;
  z-index: 1;
}

section.cta .cta-content h2 {
  font-size: 50px;
  max-width: 450px;
  margin-top: 0;
  margin-bottom: 25px;
  color: white;
}

@media (min-width: 768px) {
  section.cta .cta-content h2 {
    font-size: 80px;
  }
}

section.cta .overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
}

section.contact {
  text-align: center;
}

section.contact h2 {
  margin-top: 0;
  margin-bottom: 25px;
}

section.contact h2 i {
  color: #dd4b39;
}

section.contact ul.list-social {
  margin-bottom: 0;
}

section.contact ul.list-social li a {
  font-size: 40px;
  line-height: 80px;
  display: block;
  width: 80px;
  height: 80px;
  color: white;
  border-radius: 100%;
}

section.contact ul.list-social li.social-twitter a {
  background-color: #1da1f2;
}

section.contact ul.list-social li.social-twitter a:hover {
  background-color: #0d95e8;
}

section.contact ul.list-social li.social-facebook a {
  background-color: #3b5998;
}

section.contact ul.list-social li.social-facebook a:hover {
  background-color: #344e86;
}

section.contact ul.list-social li.social-google-plus a {
  background-color: #dd4b39;
}

section.contact ul.list-social li.social-google-plus a:hover {
  background-color: #d73925;
}

footer {
  padding: 25px 0;
  text-align: center;
  color: rgba(255, 255, 255, 0.3);
  background-color: #222222;
}

footer p {
  font-size: 12px;
  margin: 0;
}

footer ul {
  margin-bottom: 0;
}

footer ul li a {
  font-size: 12px;
  color: rgba(255, 255, 255, 0.3);
}

footer ul li a:hover, footer ul li a:focus, footer ul li a:active, footer ul li a.active {
  text-decoration: none;
}

.bg-primary {
  background: #fdcc52;
  background: linear-gradient(#fdcc52, #fdc539);
}

.text-primary {
  color: #fdcc52;
}

.no-gutter > [class*='col-'] {
  padding-right: 0;
  padding-left: 0;
}

.btn-outline {
  color: white;
  border: 1px solid;
  border-color: white;
}

.btn-outline:hover, .btn-outline:focus, .btn-outline:active, .btn-outline.active {
  color: white;
  border-color: #fdcc52;
  background-color: #fdcc52;
}

.btn {
  border-radius: 300px;
  font-family: 'Lato', 'Helvetica', 'Arial', 'sans-serif';
  letter-spacing: 2px;
  text-transform: uppercase;
}

.btn-xl {
  font-size: 11px;
  padding: 15px 45px;
}

# The Good Fridge Project
## DH 150 UX Design, Wendy Li

## Introduction: 
My project would help users set personalized ethical goals regarding their own food consumption. This app serves the function of fulfilling the human need for self actualization via food consumption rather than their physiological needs. 

## Design Statement:
The food consumer culture in America has evolved towards greater awareness of ethical issues such as environmental issues/sustainability, human rights issues (fair trade), and animal rights issues. Current solutions that help humans set ethical food consumption goals tend to focus on one type of goal. For instance, there are apps that help people become vegetarians, or diminish carbon foodprint, but there are no apps that enables its users to set a comprehensive set of goals that guides them to become a better person in alignment with their value systems. Existing apps also oftentimes dictate one standard of ethical eating, and doesn't allow its users to customize their consumption of food based on their personal ethical priorities. This app would allow users to customize what's important to them. Furthermore, the app will diminish the enormous information barriers for users so that they wouldn't have to conduct comprehensive research in order to find out how to achieve their ethical goals. This app will help users set personal goals, and provide customizable plans to help them achieve these goals.

## Competitor Analysis: 
Competitor apps that similarly tracks and changes users behaviors include: The Fitness Pal, and My Plate. 
https://github.com/wendyli328/DH150/blob/master/SampleHeuristics.md
https://github.com/wendyli328/DH150/blob/master/SampleUsabilityTesting.md

## User Research:
From this contexual analysis, I learned that it's very difficult for users to have the initial motivation to go onto an app that will change their habits and lifestyle. Also, convenience is extremely important to users in habit tracking apps. In addition, financial constraints is a major obstacle preventing users from making ethical choices.

Next time, I would like to think of ways to ask questions that doesn't sound like I'm blaming them or judging them for their food choices. I feel like asking questions about whether they care about the environment can make my interviewee feel like I'm judging them if they don't, and they feel awkward answering that question. In addition, I'd like to observe more how they make plans to eat with friends, and how a group of friends decide where to go out to eat together.
https://github.com/wendyli328/DH150/blob/master/Contexual-Inquiry/2.md

## UX Storytelling:
From creating scenarios and personas, I was able to hone down on the key features that I want to include in my wireframes. 

![scenario 1](https://github.com/wendyli328/DH150/blob/master/Scenario%201-page-001.jpg)
![scenario 2](https://github.com/wendyli328/DH150/blob/master/Scenario%202-page-001.jpg)
![scenario 3](https://github.com/wendyli328/DH150/blob/master/Scenario%203-page-001.jpg) 

![persona 1](https://github.com/wendyli328/DH150/blob/master/Persona%201-page-001.jpg)
![persona 2](https://github.com/wendyli328/DH150/blob/master/Persona%202-page-001.jpg)
![persona 3](https://github.com/wendyli328/DH150/blob/master/Persona%203.jpg)


## Wireframe and graphic design element variation:
https://github.com/wendyli328/DH150/tree/master/assignment07

## Low-fidelity Prototype 
I did a few versions of low-fidelity prototypes. It was difficult to decide what key features can make the minimap viable product, and how to build my information architect in the way that's easiest to follow. During this process, i frequently researched the layout of other apps to draw inspiration. 

Wireframe (Sketch):
![Image of drawing](https://github.com/wendyli328/DH150/blob/master/Screen%20Shot%202020-02-16%20at%203.15.57%20PM.jpg)

Wireframe (Figma):
![Image of Wireframes](https://github.com/wendyli328/DH150/blob/master/Screen%20Shot%202020-02-16%20at%203.11.35%20PM.jpg)

https://github.com/wendyli328/DH150/blob/master/LoFiPrototype.md

## High-fidelity Prototype
I made two versions of my high-fidelity prototype. I was unhappy with my first one but didn't know how to fix it. On my second try, I started using Adobe Illustrator as an additional tool to Figma, and also carefully studied the designs of my favorite app "Headspace." The animation on my high fidelity prototype was inspired by them.
Version 1: https://www.figma.com/file/H0bPNnnqnwFhrvZVXGQ689/First-Draft?node-id=0%3A1
Version 2: https://www.figma.com/proto/5bBrzsvZBtRhcJQkxBVB46/Third-Draft?node-id=28%3A6&scaling=scale-down

## Pitch video [update the video after recording your presentation]
https://www.youtube.com/watch?v=x9HzxSUGfUo
https://www.youtube.com/watch?v=LKJKVY8N0es

## Conclusion:
I learned that UI UX design is in many ways a scientific pursuit. It involves research, repeated testings, evaluation, etc. It's not simply seeing that something looks good or feeling like something works and implementing it. I learned from this class that UI UX is systematic and disciplined. Through this class, I gained a better understanding of where and how to start my own independent projects. It gave me the tools to create something that I can otherwise just imagine. 
