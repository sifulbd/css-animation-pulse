
![Screen Shot 2019-04-08 at 18 12 32](https://user-images.githubusercontent.com/8652443/55723111-f4e02500-5a29-11e9-8a88-208b5ca4ade3.png)



## ====== HTML Codes =====

```html
<!DOCTYPE html>
<html lang="en" >

<head>
  <meta charset="UTF-8">
  <title>CSS animation pulse</title>  
  <link rel="stylesheet" href="css/style.css">
  
</head>
	<body>
		<div class="box">Dot</div>
	</body>
</html>

```

## ===== CSS Codes ========

```css
.box {
  top: 50%;
  right: 50%;
  width: 100px;
  height: 100px;
  line-height: 100px;
  text-align: center;
  background: #fff;
  position: absolute;
  border-radius: 100%;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
  -webkit-box-shadow: 0px 0px 30px 1px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 0px 30px 1px rgba(0, 0, 0, 0.3);
}
.box:before {
  top: 0px;
  left: 0px;
  z-index: -1;
  content: '';
  width: 100%;
  height: 100%;
  position: absolute;
  border-radius: 100%;
  -webkit-animation: pulse 2.5s infinite cubic-bezier(0.4, 0, 1, 1) both;
  animation: pulse 2.5s infinite cubic-bezier(0.4, 0, 1, 1) both;
}

```

## The Animation code

```css

-webkit-keyframes scale {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1); }
  50% {
    -webkit-transform: scale(1.1);
    transform: scale(1.1); }
  100% {
    -webkit-transform: scale(1);
    transform: scale(1); } }
@keyframes scale {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1); }
  50% {
    -webkit-transform: scale(1.1);
    transform: scale(1.1); }
  100% {
    -webkit-transform: scale(1);
    transform: scale(1); } }

@-webkit-keyframes pulse {
  0% {
    -webkit-box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0.3);
    box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0.3); }
  50% {
    -webkit-box-shadow: 0px 0px 0px 50px rgba(255, 77, 28, 0);
    box-shadow: 0px 0px 0px 50px rgba(255, 77, 28, 0); }
  100% {
    -webkit-box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0);
    box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0); } }

@keyframes pulse {
  0% {
    -webkit-box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0.3);
    box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0.3); }
  50% {
    -webkit-box-shadow: 0px 0px 0px 50px rgba(255, 77, 28, 0);
    box-shadow: 0px 0px 0px 50px rgba(255, 77, 28, 0); }
  100% {
    -webkit-box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0);
    box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0); } }

@-webkit-keyframes pulse2 {
  0% {
    -webkit-box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0.2);
    box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0.2); }
  50% {
    -webkit-box-shadow: 0px 0px 0px 100px rgba(255, 77, 28, 0);
    box-shadow: 0px 0px 0px 100px rgba(255, 77, 28, 0); }
  100% {
    -webkit-box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0);
    box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0); } }

@keyframes pulse2 {
  0% {
    -webkit-box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0.2);
    box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0.2); }
  50% {
    -webkit-box-shadow: 0px 0px 0px 100px rgba(255, 77, 28, 0);
    box-shadow: 0px 0px 0px 100px rgba(255, 77, 28, 0); }
  100% {
    -webkit-box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0);
    box-shadow: 0px 0px 0px 0px rgba(255, 77, 28, 0); } }

```
 

 A Pen created at CodePen.io. You can find this one at [Live on Codepen](https://codepen.io/sifulislam/pen/pBEBvP).

