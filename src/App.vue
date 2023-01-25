<template>
<nav>
  <div class="nav-wrapper">
    <a href="#" class="brand-logo">Logo</a>
    <ul id="nav-mobile" class="right hide-on-med-and-down">
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/about">About</router-link></li>
      <li><a href="collapsible.html">JavaScript</a></li>
    </ul>
  </div>
</nav>
<div class="container">
  <div class="row">
    <div class="col s6">
      <p> hell world a;osierq qpouweb qpoweubrpq pqiwuebr qowuebr qweporh </p>
    </div>
    <div class="col s6">
      <p> hell world a;osierq qpouweb qpoweubrpq pqiwuebr qowuebr qweporh </p>
    </div>
    <div class="col s6">
      <p> hell world a;osierq qpouweb qpoweubrpq pqiwuebr qowuebr qweporh </p>
    </div>
  </div>
  <div class="carousel">
    <a class="carousel-item" href="#one!"><img src="https://images.unsplash.com/photo-1611915387288-fd8d2f5f928b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxleHBsb3JlLWZlZWR8MXx8fGVufDB8fHx8&w=1000&q=80"></a>
    <a class="carousel-item" href="#two!"><img src="https://images.unsplash.com/photo-1611915387288-fd8d2f5f928b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxleHBsb3JlLWZlZWR8MXx8fGVufDB8fHx8&w=1000&q=80"></a>
    <a class="carousel-item" href="#three!"><img src="https://images.unsplash.com/photo-1611915387288-fd8d2f5f928b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxleHBsb3JlLWZlZWR8MXx8fGVufDB8fHx8&w=1000&q=80"></a>
    <a class="carousel-item" href="#four!"><img src="https://lorempixel.com/250/250/nature/4"></a>
    <a class="carousel-item" href="#five!"><img src="https://lorempixel.com/250/250/nature/5"></a>
  </div>

  <router-view/>
</div>
</template>

<script>
import M from 'materialize-css'

export default {
  name: 'app',
  mounted () {
    M.AutoInit()
  }
}
</script>

<style>
</style>
