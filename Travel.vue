<template>
  <div>
  <!-- The slideshow/carousel -->
    <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
     <div class="carousel-item active">
 		    <img class="bd-placeholder-img" src="../assets/Firenze.jpg" width="100%" height="100%"/>
        <div class="container">
          <div class="carousel-caption text-start">
            <h1>Firenze (피렌체)</h1>
            <p>이탈리아 토스카나주의 주도. 이탈리아 르네상스의 본고장으로 불리기도 한다</p>
          </div>
        </div>
     </div>
     <div class="carousel-item">
      	<img class="bd-placeholder-img" src="../assets/Etretat.jpg" width="100%" height="100%"/>
        <div class="container">
          <div class="carousel-caption text-center">
            <h1>에트르타 (Etretat)</h1>
            <p>팔레즈 다발 & 팔레즈 다몽. 흰절벽과 바다의 풍경이 어우러진 에트르타의 절경</p>
          </div>
        </div>
      </div>
      <div class="carousel-item">
		    <img class="bd-placeholder-img" src="../assets/Moulins.jpg" width="100%" height="100%"/>
        <div class="container">
          <div class="carousel-caption text-center">
            <h1>물랭 (Moulins)</h1>
            <p>프랑스 알리에주의 주도이며 프랑스 중부에 위치해 있다</p>
          </div>
        </div>
      </div>
    </div>
    <!-- <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button> -->
    <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>

  <hr>
  <footer>2021 COPYRIGHTⓒTRAVELN.&nbsp;ALL RIGHTS RESERVED</footer>
</div>
</template>

<style>
/* CUSTOMIZE THE CAROUSEL
-------------------------------------------------- */

/* Carousel base class */
.carousel {
  margin-bottom: 4rem;
  margin-top: 50px;
}
/* Since positioning the image, we need to help out the caption */
.carousel-caption {
  bottom: 3rem;
  z-index: 10;
}

/* Declare heights because of positioning of img element */
.carousel-item {
  height: 32rem;
}
.carousel-item > img {
  position: absolute;
  top: 0;
 left:0;
  min-width: 100%;
  height: 32rem;
}

/* RESPONSIVE CSS
-------------------------------------------------- */

@media (min-width: 40em) {
  /* Bump up size of carousel content */
  .carousel-caption p {
    margin-bottom: 1.25rem;
    font-size: 1.25rem;
    line-height: 1.4;
  }

  .featurette-heading {
    font-size: 50px;
  }
}

@media (min-width: 62em) {
  .featurette-heading {
    margin-top: 7rem;
  }
}
</style>
