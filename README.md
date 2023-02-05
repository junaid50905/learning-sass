# learning-sass

## Difference between sass, scss and css

![Logo](https://qph.cf2.quoracdn.net/main-qimg-cb41710b11523148a80f95f38a5c81ae)

## Variable
### scss
``` scss
//Variables
$primary : red;
$heading_size : calc(50px + 10vw);

h1{
    color: $primary;
    font-size: $heading_size;
}

```

## @import
index.html
![Logo](https://i.ibb.co/MP9Zyq4/scss-import-index.png)
imported files
![Logo](https://i.ibb.co/qxCZ3mH/Screenshot-20230205-125210.png)
main.scss
![Logo](https://i.ibb.co/9wDNdv9/scss-import-main.png)
main.css
![Logo](https://i.ibb.co/wyPXFCy/scss-import-main-css.png)


#### Note: file gula ke main.scss file jei serial a rakha hobe, oi serial ei main.css a pabe.

#### main.scss jei folder/path a ache baki file gulo same folder a thakle file er name er sathe _ diye file er nam shuro korbo. oi file gulo ke main.scss file a rakhar somoy shudo file er nam dilei hobe. ar jodi file gulo onno folder/path a thake tokhon directory diye import korte hobe. tokhon _ deya lagbe nah

## @mixin @include
![Logo](https://i.ibb.co/ZJzhzcB/mixin-include.png)
mixin works like a function and include is used to call that function

here is the result of mixin and include:
![Logo](https://i.ibb.co/8jq1LPz/Screenshot-20230205-013938.png)
