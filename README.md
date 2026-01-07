# Ex09 Event Registration Web Application
## Date:25/12/2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
page1.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="element">
      <img class="logo-sec" src="img/logo-sec-1.png" />
      <img class="logo" src="img/logo-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">PONGAL CELEBRATION EVENT</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <img class="po" src="img/po2-1.png" />
      <div class="text-wrapper-2">LOGIN</div>
      <div class="text-wrapper-3">REGISTER</div>
    </div>
  </body>
</html>

pag1.css

.element {
  background-color: #7bdcf2;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.element .logo-sec {
  position: absolute;
  top: 1px;
  left: 0;
  width: 412px;
  height: 83px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.element .logo {
  position: absolute;
  top: 118px;
  left: 126px;
  width: 160px;
  height: 159px;
  aspect-ratio: 1;
  object-fit: cover;
}

.element .rectangle {
  position: absolute;
  top: 311px;
  left: 15px;
  width: 381px;
  height: 41px;
  background-color: #f2a2d7ed;
}

.element .text-wrapper {
  position: absolute;
  top: 318px;
  left: 76px;
  font-family: "Moon Dance-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .div {
  position: absolute;
  top: 406px;
  left: 111px;
  width: 190px;
  height: 31px;
  background-color: #d91e82;
}

.element .rectangle-2 {
  position: absolute;
  top: 471px;
  left: 111px;
  width: 190px;
  height: 31px;
  background-color: #cf0075;
}

.element .po {
  position: absolute;
  top: 590px;
  left: 111px;
  width: 190px;
  height: 190px;
  aspect-ratio: 1;
  object-fit: cover;
}

.element .text-wrapper-2 {
  position: absolute;
  top: 404px;
  left: 167px;
  font-family: "Moul-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .text-wrapper-3 {
  position: absolute;
  top: 469px;
  left: 146px;
  font-family: "Moul-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

page2.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="element">
      <img class="po" src="img/po5-1.png" />
      <div class="text-wrapper">PONGAL CELEBRATION EVENT</div>
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <img class="star-4" src="img/star-5.svg" />
      <img class="star-5" src="img/star-6.svg" />
      <img class="star-6" src="img/star-7.svg" />
      <img class="star-7" src="img/star-8.svg" />
      <div class="div">pongal cooking</div>
      <div class="text-wrapper-2">Tug of war</div>
      <div class="text-wrapper-3">Rangoli</div>
      <div class="text-wrapper-4">Uriyadi</div>
      <div class="text-wrapper-5">Singing</div>
      <div class="text-wrapper-6">Traditional dance</div>
      <div class="text-wrapper-7">Musical chair</div>
      <div class="text-wrapper-8">Kabaddi</div>
    </div>
  </body>
</html>

page2.css

.element {
  background-color: #ffffff;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.element .po {
  position: absolute;
  top: 0;
  left: 0;
  width: 412px;
  height: 917px;
  aspect-ratio: 1;
  object-fit: cover;
}

.element .text-wrapper {
  position: absolute;
  top: 79px;
  left: 76px;
  font-family: "Moon Dance-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .star {
  top: 134px;
  left: 59px;
  position: absolute;
  width: 33px;
  height: 24px;
}

.element .img {
  top: 512px;
  left: 60px;
  position: absolute;
  width: 33px;
  height: 24px;
}

.element .star-2 {
  top: 458px;
  left: 58px;
  position: absolute;
  width: 33px;
  height: 24px;
}

.element .star-3 {
  top: 404px;
  left: 59px;
  position: absolute;
  width: 33px;
  height: 24px;
}

.element .star-4 {
  top: 350px;
  left: 58px;
  position: absolute;
  width: 33px;
  height: 24px;
}

.element .star-5 {
  top: 296px;
  left: 60px;
  position: absolute;
  width: 33px;
  height: 24px;
}

.element .star-6 {
  top: 242px;
  left: 60px;
  position: absolute;
  width: 33px;
  height: 24px;
}

.element .star-7 {
  top: 188px;
  left: 60px;
  position: absolute;
  width: 33px;
  height: 24px;
}

.element .div {
  position: absolute;
  top: 132px;
  left: 115px;
  font-family: "Limelight-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .text-wrapper-2 {
  position: absolute;
  top: 186px;
  left: 115px;
  font-family: "Limelight-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .text-wrapper-3 {
  position: absolute;
  top: 240px;
  left: 115px;
  font-family: "Limelight-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .text-wrapper-4 {
  position: absolute;
  top: 296px;
  left: 115px;
  font-family: "Limelight-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .text-wrapper-5 {
  position: absolute;
  top: 348px;
  left: 115px;
  font-family: "Limelight-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .text-wrapper-6 {
  position: absolute;
  top: 404px;
  left: 115px;
  font-family: "Limelight-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .text-wrapper-7 {
  position: absolute;
  top: 456px;
  left: 115px;
  font-family: "Limelight-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.element .text-wrapper-8 {
  position: absolute;
  top: 511px;
  left: 115px;
  font-family: "Limelight-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

page3.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="element">
      <img class="po" src="img/po3-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-2">NAME</div>
      <div class="text-wrapper-3">REGISTER NUM</div>
      <div class="text-wrapper-4">CONTACT NUM</div>
      <div class="text-wrapper-5">GENDER</div>
      <div class="text-wrapper-6">EMAIL</div>
      <div class="text-wrapper-7">AGE</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-8">EVENTS REGISTERED</div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-9">SUBMIT</div>
    </div>
  </body>
</html>

page3.css

.element {
  background-color: #8ec5a5;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.element .po {
  position: absolute;
  top: 11px;
  left: 0;
  width: 412px;
  height: 906px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.element .rectangle {
  position: absolute;
  top: 14px;
  left: 13px;
  width: 390px;
  height: 43px;
  background-color: #030303;
}

.element .text-wrapper {
  position: absolute;
  top: 24px;
  left: 80px;
  font-family: "Lilita One-Regular", Helvetica;
  font-weight: 400;
  color: #dfdada;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.element .div {
  position: absolute;
  top: 143px;
  left: 87px;
  width: 235px;
  height: 39px;
  background-color: #d9d9d9;
}

.element .rectangle-2 {
  position: absolute;
  top: 431px;
  left: 87px;
  width: 235px;
  height: 39px;
  background-color: #d9d9d9;
}

.element .rectangle-3 {
  position: absolute;
  top: 503px;
  left: 87px;
  width: 235px;
  height: 39px;
  background-color: #d9d9d9;
}

.element .rectangle-4 {
  position: absolute;
  top: 359px;
  left: 87px;
  width: 235px;
  height: 39px;
  background-color: #d9d9d9;
}

.element .rectangle-5 {
  position: absolute;
  top: 287px;
  left: 87px;
  width: 235px;
  height: 39px;
  background-color: #d9d9d9;
}

.element .rectangle-6 {
  position: absolute;
  top: 215px;
  left: 87px;
  width: 235px;
  height: 39px;
  background-color: #d9d9d9;
}

.element .text-wrapper-2 {
  position: absolute;
  top: 151px;
  left: 177px;
  font-family: "Lilita One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.element .text-wrapper-3 {
  position: absolute;
  top: 223px;
  left: 144px;
  font-family: "Lilita One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.element .text-wrapper-4 {
  position: absolute;
  top: 513px;
  left: 140px;
  font-family: "Lilita One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.element .text-wrapper-5 {
  position: absolute;
  top: 367px;
  left: 173px;
  font-family: "Lilita One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.element .text-wrapper-6 {
  position: absolute;
  top: 436px;
  left: 176px;
  font-family: "Lilita One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.element .text-wrapper-7 {
  position: absolute;
  top: 293px;
  left: 187px;
  font-family: "Lilita One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.element .rectangle-7 {
  position: absolute;
  top: 575px;
  left: 87px;
  width: 235px;
  height: 45px;
  background-color: #d9d9d9;
}

.element .text-wrapper-8 {
  position: absolute;
  top: 586px;
  left: 116px;
  font-family: "Lilita One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.element .rectangle-8 {
  position: absolute;
  top: 775px;
  left: 110px;
  width: 192px;
  height: 49px;
  background-color: #d9d9d9;
}

.element .text-wrapper-9 {
  position: absolute;
  top: 788px;
  left: 170px;
  font-family: "Lilita One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```


## OUTPUT:
![WhatsApp Image 2026-01-07 at 3 25 45 PM](https://github.com/user-attachments/assets/accab56a-c674-42ac-a1fb-ef28488e22a9)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
