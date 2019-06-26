# masonry-gallery

#Estructura
```
<div class="container-fluid">
    <div class="row">
      <div class="col-md-12">
         <div class="mansory">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/mWpE3Q/2.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/mysOxk/3.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/mWpE3Q/2.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/mysOxk/3.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/mysOxk/3.jpg" alt="">
            <img src="https://preview.ibb.co/mysOxk/3.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/i0PmHk/1.jpg" alt="">
            <img src="https://preview.ibb.co/mWpE3Q/2.jpg" alt="">
         </div>
       </div>
    </div>
  </div>
  ```
  #CSS (Obligatorio)
  
  El atributo de css column-count es el que determina el numero de columna se puede modificar por el que desees y a su vez tendra que modificar lo mismo en las media query para el responsive.
  
  ```
   .mansory {
     -webkit-column-count: 4; /* Chrome, Safari, Opera */
     -moz-column-count: 4; /* Firefox */
     column-count: 4;
  }
  .mansory img{ width: 100%; padding: 7px 0;}
  @media (max-width: 1200px) {
    .mansory {
      -webkit-column-count: 3; /* Chrome, Safari, Opera */
      -moz-column-count: 3; /* Firefox */
      column-count: 3;
  }
  @media (max-width: 992px) {
    .mansory {
      -webkit-column-count: 2; /* Chrome, Safari, Opera */
      -moz-column-count: 2; /* Firefox */
      column-count: 2;
  }
  @media (max-width: 720px) {
    .mansory {
      -webkit-column-count: 1; /* Chrome, Safari, Opera */
      -moz-column-count: 1; /* Firefox */
      column-count: 1;
     }
  }
  ```
