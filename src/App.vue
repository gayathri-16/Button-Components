<template>
  <div>
    <link  rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.css" />
   <link href="https://fonts.googleapis.com/css2? amily=Baloo+Thambi+2:wght@500&family=Montaga&family=Tajawal&display=swap" rel="stylesheet">
   <link href="https://fonts.googleapis.com/css2?family=Philosopher:wght@400;700&display=swap" rel="stylesheet">
    <h1 class="title">Buttons</h1>
      
    <div class="button-types">
      <h2 class="buttons">Colors</h2>
      
      <h2 class="buttons">Typography</h2>
      <h2 class="buttons">Spaces</h2>
      <h2 class="buttons">Buttons</h2>
      <h2 class="buttons"><b style="color:rgb(5, 13, 63);">Inputs</b></h2>
      <h2 class="buttons">Grid</h2>
    </div>

<div class="back-color">
  <h3 class="abt-btn"> <i class="fas fa-angle-left"></i> Buttons / <i class="fas fa-angle-right"></i> </h3>
  <button class="normal">Default</button>
  <h4 class="effect-btn">&:hover, &:focus</h4>
  <button class="effect">Default</button>
</div> <br>
<div class="outline-btn">
  <h3 class="abt-btn"> <i class="fas fa-angle-left"></i> Buttons variants="outline" / <i class="fas fa-angle-right"></i> </h3>
  <button class="normal outline">Default</button>
  <h4 class="effect-btn">&:hover, &:focus</h4>
  <button class="effect out-hov">Default</button>
</div> <br>
<div class="text-btn">
  <h3 class="abt-btn"> <i class="fas fa-angle-left"></i> Buttons variants="text" / <i class="fas fa-angle-right"></i> </h3>
  <button class="varient">Default</button>
  <h4 class="effect-btn">&:hover, &:focus</h4>
  <button class="effect var-text">Default</button>
</div> <br>
<div class="disable-btn">
  <h3 class="abt-btn"> <i class="fas fa-angle-left"></i> Buttons disableShadow / <i class="fas fa-angle-right"></i> </h3>
  <button class="disabled">Default</button>
    <h4 class="effect-btn d-text"><i class="fas fa-angle-left"></i> Buttons disabled/ <i class="fas fa-angle-right"></i> </h4>
  <button class="effect dis-hov">Disabled</button>
   <h4 class="effect-btn d-btn"><i class="fas fa-angle-left"></i> Buttons varient="text" disabled/ <i class="fas fa-angle-right"></i> </h4>
     <button class="effect disabled d-hover">Disabled</button>
</div> <br>
<div class="text-btn">
   <h4 class="effect-btn d-text grocery"> <i class="fas fa-angle-left"></i> Buttons endIcon="local_grocery_store" / <i class="fas fa-angle-right"></i> </h4>
   <button class="disabled"><i id="icon" class="fas fa-cart-plus"></i>Default</button>
    <h4 class="effect-btn d-text grocery1"> <i class="fas fa-angle-left"></i> Buttons endIcon="local_grocery_store" / <i class="fas fa-angle-right"></i> </h4>
   <button class="effect endi">Default<i id="icon" class="fas fa-cart-plus"></i></button>
</div> <br> <br>

<div class="size-btn">
  <h3 class="abt-btn size"> <i class="fas fa-angle-left"></i> Buttons size="sm" / <i class="fas fa-angle-right"></i> </h3>
  <button class="normal sm-btn">Default</button>
<h3 class="abt-btn md size"> <i class="fas fa-angle-left"></i> Buttons  size="md" / <i class="fas fa-angle-right"></i> </h3>
  <button class="normal md-btn">Default</button>
<h3 class="abt-btn size lg"> <i class="fas fa-angle-left"></i> Buttons size="lg" / <i class="fas fa-angle-right"></i> </h3>
  <button class="normal lg-btn">Default</button>
</div> <br> <br> <br>
<div class="size-btn">
  <h3 class="abt-btn size-txt"> <i class="fas fa-angle-left"></i> Buttons color="default" / <i class="fas fa-angle-right"></i> </h3>
  <button class="normal md-btn default">Default</button>
<h3 class="abt-btn md size-txt1"> <i class="fas fa-angle-left"></i> Buttons  color="primary" / <i class="fas fa-angle-right"></i> </h3>
  <button class="normal primary">Default</button>
<h3 class="abt-btn lg size-txt2"> <i class="fas fa-angle-left"></i> Buttons color="secondry" / <i class="fas fa-angle-right"></i> </h3>
  <button class="normal secondry">Secondry</button>
  <h3 class="abt-btn alert"> <i class="fas fa-angle-left"></i> Buttons color="danger" / <i class="fas fa-angle-right"></i> </h3>
  <button class="normal danger">Danger</button>
</div> 
<div class="size-btn">
     <h4 class="effect-btn d-text grocery" style="font-size:18px;letter-spacing:2px;"> &:hover, &:focus </h4>
   <button class=" primary-hov">Default</button>
   <button class="one">Default</button>
   <button class="two">Secondry</button>
   <button class="three">Danger</button>
 </div> <br> <br>


  </div>
</template>

<script>
  export default {
    
  }
</script>

<style>

.title{
  text-align:center;
  font: 40px ;
  font-family: 'Fugaz One', cursive;
  font-weight:700px;
}
.button-types{
  margin:5rem;
}
.buttons{
font-size:24px;
color:rgb(75, 75, 75);
line-height: 70px;

font-family: 'Philosopher', sans-serif;

}
.back-color{
   margin-left:30rem;
   margin-top:-40rem;
}
.abt-btn{
  font-size:26px;
  font-family:'Tajawal', sans-serif;
  
}
.effect-btn{
  margin-left:28rem;
  margin-top:-7rem;
  font-size:20px;
  font-family: 'Montaga', serif;
  letter-spacing: 2px;
}
button{
width:150px;
  height:50px;
  border-radius:10px;
  border-style:none;
  background:rgb(223, 223, 223);
font-family: 'Baloo Thambi 2', cursive;
font-size:20px;
}

.effect{
  margin-left:28rem;
  margin-top:0.5rem;
  border-style:none;
  
}
.effect:hover{
  box-shadow:0 0 2px rgb(202, 200, 200);
  background:gray;
  transform: translateY(-5px);
  transition:1s;

}

.effect:focus{
  box-shadow:0 0 2px rgb(75, 75, 75);
  background:gray;
  transform: translateY(-5px);
  transition:2s;
  border: style 0px;

}
.outline-btn{
  margin-left:30rem;
  margin-top:4rem;
}
.outline{
background:transparent;
border:1px solid rgb(0, 102, 255);
color:rgb(0, 102, 255);

}
.out-hov{
  background:transparent;
  border:1px solid rgb(0, 102, 255);
  color:rgb(0, 102, 255);
}
.out-hov:hover{
  background:rgb(179, 214, 255);

}
.text-btn{
  margin-left:30rem;
  margin-top:4rem;
}
.varient{
  background:transparent;
color:rgb(0, 102, 255);
}
.var-text{
   background:transparent;
color:rgb(0, 102, 255);
}
.var-text:hover{
background:rgb(179, 214, 255);

}
.disable-btn{
 margin-left:30rem;
  
}
.disabled{
  background:rgb(0, 102, 255);
  color:white;
  margin-left:0.1rem;
}
.dis-hov{
  margin-left:0.1rem;
}
.dis-hov:hover{
  background:rgb(194, 194, 194);
  color:rgb(99, 99, 99);
}
.d-hover{
    margin-left:30rem;
}
.d-hover:hover
{
  background:transparent;
  color:rgb(99, 99, 99);
  cursor:pointer;

}
.d-btn{
  margin-left:25rem;
}
.d-text{
  margin-left:0.1rem;
  margin-top:6rem;

}
#icon{
  color:white;
  font-size:20px;
  margin:1rem;
}
.endi{
   background:rgb(0, 102, 255);
  color:white;
margin-left:34rem;
}
.grocery{
  font-size:18px;
  letter-spacing: 0ch;
}
.grocery1{
   font-size:18px;
  letter-spacing: 0ch;
  margin-left:28rem;
  margin-top:-5.9rem;

}
.size-btn{
  margin-left:30rem;
  
}
.sm-btn{
  width:80px;
  font-size:14px;
  color:white;
  background: rgb(0,102,255);
  margin-left:1.5rem;
}
.md{
  margin-left:15rem;
  margin-top:-6.1rem;
}
.md-btn{
  margin-left:17rem;
  width:120px;
  font-size:18px;
  color:white;
  background: rgb(0,102,255);

}
.lg{
  margin-left:31rem;
  margin-top:-6.1rem;
}
.lg-btn{
   margin-left:32rem;
   width:180px;
  font-size:24px;
  color:white;
  background: rgb(0,102,255);

}

.size{
  font-size:20px;
}
.alert{
  font-size:18px;
  margin-left:48rem;
  margin-top:-5.8rem;
  
}
.primary-hov{
  background:rgb(203, 204, 203);
}
.primary-hov:hover{
  background: gray;
}
.one{
  width:130px;
  background: rgb(0,102,255);
  color:white;
  margin-left:7.6rem;
}
.one:hover{
  background: blue;
  transform: translateY(-5px);
  transition:1s;

}
.two{
  width:180px;
  margin-left:7.3rem;
  background:gray;
  color:white;
}
.two:hover{
  background:rgb(9, 31, 9);
  transform: translateY(-5px);
  transition:1s;

}
.secondry{
width:180px;
 margin-left:32rem;
 background:rgb(117, 116, 116);
 color:white;
}
.three{
  width:160px;
  margin-left:5.5rem;
  background:red;
  color:white;
}
.three:hover{
  background:rgb(131, 6, 6);
  transform: translateY(-5px);
  transition:1s;

}
.danger{
  background:red;
  margin-left:49rem;
  color:white;
}
.danger-hov{
  background:red;
  margin-left:49rem;
  color:white;
  
}
.danger-hov:hover{
  background: rgb(133, 3, 3);
}

.size-txt{
  font-size:18px;
}
.size-txt1{
  font-size:18px;
  margin-top:-5.8rem;
}
.size-txt2{
  font-size:18px;
   margin-top:-5.8rem;
}

</style>