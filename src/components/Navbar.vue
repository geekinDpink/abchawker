<template>
  <nav>
    <div class="nav-item"><a href="#">Home</a></div>
    <div class="nav-item"><a href="#">Blog</a></div>
    <div class="nav-item"><a href="#">Stall Info</a></div>
    <div class="nav-item"><a href="#">Join Us</a></div>
    <div class="nav-item"><a href="#">Contact Us</a></div>

  </nav>
</template>


<style>
nav {
  display: flex;
  align-items: center;
  justify-content: center;
}
nav .nav-item {
  color: #FFF;
  padding: 10px 20px;
  position: relative;
  text-align: center;
  border-bottom: 3px solid transparent;
  display: flex;
  transition: 0.4s;
}
nav .nav-item.active,
nav .nav-item:hover {
  background-color: #444;
  border-bottom-color: #FF5858;
}
nav .nav-item a {
  color: inherit;
  text-decoration: none;
}
</style>