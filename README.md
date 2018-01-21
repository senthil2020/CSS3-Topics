# CSS3-Topics
CSS3-Topics
1. Flex Box,


Flex Box :

Example : (Single Row with dynamic width)

CSS :
-------
.container {
display:flex;
flex-direction:row;
flex-wrap:nowrap;
//flex-flow:row nowrap;
}

.box {
flex:1 0 auto;
min-width:100px !important;
max-width:200px !important;
}

HTML :
-------
<div class="container">
  <div class="box"></div>
  <div class="box"></div>
  <div class="box"></div>
</div>
