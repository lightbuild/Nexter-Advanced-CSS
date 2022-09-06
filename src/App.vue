<script setup lang="ts">

</script>

<template>
  <div class="container">
    <div class="sidebar">
      <button class="nav-btn"></button>
    </div>
    
    <header class="header">
      <img src="./assets/images/logo.png" alt="Nexter Logo" class="header__logo">
      <h3 class="heading-3">Your own home:</h3>
      <h1 class="heading-1">The ultimate personal freedom</h1>
      <button class="btn header__btn">View our properties</button>
      <div class="header__seenon-text">Seen on</div>
      <div class="header__seenon-logos">
        <img src="./assets/images/logo-bbc.png" alt="Seen on logo 1">
        <img src="./assets/images/logo-bbc.png" alt="Seen on logo 2">
        <img src="./assets/images/logo-bbc.png" alt="Seen on logo 3">
        <img src="./assets/images/logo-bbc.png" alt="Seen on logo 4">
      </div>
    </header>
    
    <div class="realtors">
      <h3 class="heading-3">Top 3 realtors</h3>
      <div class="realtors__list">
        <img src="./assets/images/user-1.jpg" alt="Realotor 1" class="realtors__img">
        <div class="realtors__details">
          <h4 class="heading-4 heading-4--light">Erik Feinman</h4>
          <p class="realtors__sold">245 houses sold</p>
        </div>
        
        <img src="./assets/images/user-2.png" alt="Realotor 2" class="realtors__img">
        <div class="realtors__details">
          <h4 class="heading-4 heading-4--light">Kim Brown</h4>
          <p class="realtors__sold">212 houses sold</p>
        </div>
        
        <img src="./assets/images/user-3.jpg" alt="Realotor 3" class="realtors__img">
        <div class="realtors__details">
          <h4 class="heading-4 heading-4--light">Toby Ramsey</h4>
          <p class="realtors__sold">198 houses sold</p>
        </div>
      </div>
    </div>
    
    <section class="features">
      <div class="feature">
        <svg class="feature__icon">
          <use xlink:href="./assets/images/sprite.svg#icon-star"></use>
        </svg>
        <h4 class="heading-4 heading-4--dark">World's best luxury homes</h4>
        <p class="feature-text">Lorem ipsum dolor sit amet, consectetur adipisicing elitLorem ipsum dolor sit amet,
          consectetur adipisicing elit..</p>
      </div>
      <div class="feature">
        <svg class="feature__icon">
          <use xlink:href="./assets/images/sprite.svg#icon-map"></use>
        </svg>
        <h4 class="heading-4 heading-4--dark">Only the best properites </h4>
        <p class="feature-text">Lorem ipsum dolor sit amet, consectetur adipisicing elitLorem ipsum dolor sit amet,
          consectetur adipisicing elit..</p>
      </div>
      <div class="feature">
        <svg class="feature__icon">
          <use xlink:href="./assets/images/sprite.svg#icon-location-pin"></use>
        </svg>
        <h4 class="heading-4 heading-4--dark">All home sin in top location</h4>
        <p class="feature-text">Lorem ipsum dolor sit amet, consectetur adipisicing Lorem ipsum dolor sit amet,
          consectetur adipisicing elit.elit.</p>
      </div>
      <div class="feature">
        <svg class="feature__icon">
          <use xlink:href="./assets/images/sprite.svg#icon-key"></use>
        </svg>
        <h4 class="heading-4 heading-4--dark">New home in one week</h4>
        <p class="feature-text">Lorem ipsum dolor sit amet, consectetur adipisicing eliLorem ipsum dolor sit amet,
          consectetur adipisicing elit.t.</p>
      </div>
      <div class="feature">
        <svg class="feature__icon">
          <use xlink:href="./assets/images/sprite.svg#icon-bookmark"></use>
        </svg>
        <h4 class="heading-4 heading-4--dark">Top 1% realtors</h4>
        <p class="feature-text">Lorem ipsum dolor sit amet, consectetur adipisicing elitLorem ipsum dolor sit amet,
          consectetur adipisicing elit..</p>
      </div>
      <div class="feature">
        <svg class="feature__icon">
          <use xlink:href="./assets/images/sprite.svg#icon-aircraft-take-off"></use>
        </svg>
        <h4 class="heading-4 heading-4--dark">Secure payments</h4>
        <p class="feature-text">Lorem ipsum dolor sit amet, consectetur adipisicing eliLorem ipsum dolor sit amet,
          consectetur adipisicing elit.t.</p>
      </div>
    </section>
    
    <div class="story__pictures">
      <img src="./assets/images/hotel-1.jpg" alt="Couple with new house" class="story__img--1">
      <img src="./assets/images/hotel-3.jpg" alt="New house" class="story__img--2">
    </div>
    
    <div class="story__content">
      <h3 class="heading-3 mb-sm">Happy Customers</h3>
      <h2 class="heading-2 heading-2--dark mb-md">&ldquo;The best decision of our lives&rdquo;</h2>
      <p class="story__text">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias aut doloribus ea, facilis laboriosam magnam
        natus obcaecati odio, officia quae quam quas quidem quo!
      </p>
      <button class="btn story__btn">Find your own home</button>
    </div>
    
    <section class="homes">
      <div class="home">
        <img src="./assets/images/hotel-1.jpg" alt="House 1" class="home__img">
        <svg class="home__like">
          <use xlink:href="./assets/images/sprite.svg#icon-star"></use>
        </svg>
        <h5 class="home__name">Beautiful Family House</h5>
        <div class="home__location">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-location-pin"></use>
          </svg>
          <p>USA</p>
        </div>
        <div class="home__rooms">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-home"></use>
          </svg>
          <p>5 rooms</p>
        </div>
        <div class="home__area">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-chat"></use>
          </svg>
          <p>325 m<sup>2</sup></p>
        </div>
        <div class="home__price">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-key"></use>
          </svg>
          <p>$1,200,000</p>
        </div>
        <button class="btn home__btn">Contack realtor</button>
      </div>
      <div class="home">
        <img src="./assets/images/hotel-2.jpg" alt="House 1" class="home__img">
        <svg class="home__like">
          <use xlink:href="./assets/images/sprite.svg#icon-star"></use>
        </svg>
        <h5 class="home__name">Beautiful Family House</h5>
        <div class="home__location">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-location-pin"></use>
          </svg>
          <p>USA</p>
        </div>
        <div class="home__rooms">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-home"></use>
          </svg>
          <p>5 rooms</p>
        </div>
        <div class="home__area">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-chat"></use>
          </svg>
          <p>325 m<sup>2</sup></p>
        </div>
        <div class="home__price">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-key"></use>
          </svg>
          <p>$1,200,000</p>
        </div>
        <button class="btn home__btn">Contack realtor</button>
      </div>
      <div class="home">
        <img src="./assets/images/hotel-3.jpg" alt="House 1" class="home__img">
        <svg class="home__like">
          <use xlink:href="./assets/images/sprite.svg#icon-star"></use>
        </svg>
        <h5 class="home__name">Beautiful Family House</h5>
        <div class="home__location">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-location-pin"></use>
          </svg>
          <p>USA</p>
        </div>
        <div class="home__rooms">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-home"></use>
          </svg>
          <p>5 rooms</p>
        </div>
        <div class="home__area">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-chat"></use>
          </svg>
          <p>325 m<sup>2</sup></p>
        </div>
        <div class="home__price">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-key"></use>
          </svg>
          <p>$1,200,000</p>
        </div>
        <button class="btn home__btn">Contack realtor</button>
      </div>
      <div class="home">
        <img src="./assets/images/hotel-1.jpg" alt="House 1" class="home__img">
        <svg class="home__like">
          <use xlink:href="./assets/images/sprite.svg#icon-star"></use>
        </svg>
        <h5 class="home__name">Beautiful Family House</h5>
        <div class="home__location">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-location-pin"></use>
          </svg>
          <p>USA</p>
        </div>
        <div class="home__rooms">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-home"></use>
          </svg>
          <p>5 rooms</p>
        </div>
        <div class="home__area">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-chat"></use>
          </svg>
          <p>325 m<sup>2</sup></p>
        </div>
        <div class="home__price">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-key"></use>
          </svg>
          <p>$1,200,000</p>
        </div>
        <button class="btn home__btn">Contack realtor</button>
      </div>
      <div class="home">
        <img src="./assets/images/hotel-2.jpg" alt="House 1" class="home__img">
        <svg class="home__like">
          <use xlink:href="./assets/images/sprite.svg#icon-star"></use>
        </svg>
        <h5 class="home__name">Beautiful Family House</h5>
        <div class="home__location">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-location-pin"></use>
          </svg>
          <p>USA</p>
        </div>
        <div class="home__rooms">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-home"></use>
          </svg>
          <p>5 rooms</p>
        </div>
        <div class="home__area">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-chat"></use>
          </svg>
          <p>325 m<sup>2</sup></p>
        </div>
        <div class="home__price">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-key"></use>
          </svg>
          <p>$1,200,000</p>
        </div>
        <button class="btn home__btn">Contack realtor</button>
      </div>
      <div class="home">
        <img src="./assets/images/hotel-3.jpg" alt="House 1" class="home__img">
        <svg class="home__like">
          <use xlink:href="./assets/images/sprite.svg#icon-star"></use>
        </svg>
        <h5 class="home__name">Beautiful Family House</h5>
        <div class="home__location">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-location-pin"></use>
          </svg>
          <p>USA</p>
        </div>
        <div class="home__rooms">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-home"></use>
          </svg>
          <p>5 rooms</p>
        </div>
        <div class="home__area">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-chat"></use>
          </svg>
          <p>325 m<sup>2</sup></p>
        </div>
        <div class="home__price">
          <svg>
            <use xlink:href="./assets/images/sprite.svg#icon-key"></use>
          </svg>
          <p>$1,200,000</p>
        </div>
        <button class="btn home__btn">Contack realtor</button>
      </div>
    </section>
    
    <section class="gallery">
      <figure class="gallery__item gallery__item--1">
        <img src="./assets/images/hotel-1.jpg" alt="Gallery image 1" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--2">
        <img src="./assets/images/hotel-2.jpg" alt="Gallery image 2" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--3">
        <img src="./assets/images/hotel-3.jpg" alt="Gallery image 3" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--4">
        <img src="./assets/images/hotel-1.jpg" alt="Gallery image 1" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--5">
        <img src="./assets/images/hotel-2.jpg" alt="Gallery image 2" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--6">
        <img src="./assets/images/hotel-3.jpg" alt="Gallery image 3" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--7">
        <img src="./assets/images/hotel-1.jpg" alt="Gallery image 1" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--8">
        <img src="./assets/images/hotel-2.jpg" alt="Gallery image 2" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--9">
        <img src="./assets/images/hotel-3.jpg" alt="Gallery image 3" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--10">
        <img src="./assets/images/hotel-1.jpg" alt="Gallery image 1" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--11">
        <img src="./assets/images/hotel-2.jpg" alt="Gallery image 2" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--12">
        <img src="./assets/images/hotel-3.jpg" alt="Gallery image 3" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--13">
        <img src="./assets/images/hotel-1.jpg" alt="Gallery image 1" class="gallery__img">
      </figure>
      <figure class="gallery__item gallery__item--14">
        <img src="./assets/images/hotel-2.jpg" alt="Gallery image 2" class="gallery__img">
      </figure>
    </section>
    
    <footer class="footer">
      <ul class="nav">
        <li class="nav__item"><a href="#" class="nav__link">Find your dream home</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Request proposal</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Download home planner</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Contact us</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Submit your property</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Come work with us!</a></li>
      </ul>
      <p class="copyright">
        &copy;Copyright 2022 by Light Build. Feel free to use this project for your own purposes!
      </p>
    </footer>
  </div>
</template>

<style scoped>

</style>
