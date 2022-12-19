<template>
    <div class="home-page">
      <nav>
        <ul class="nav nav-pills">
          <li class="nav-item">
            <router-link to="/" class="nav-link btn">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/recipe" class="nav-link btn ">Recipe</router-link>
          </li>
        </ul>
      </nav>
      <div class="content" style="text-align: center;">
  <h1>Welcome to my Recipes App!</h1>
  <p>You will have the chance to add your recipes here!</p>
  <router-link to="/recipe" class="btn btn-dark">View Recipe</router-link>
</div>

      
    </div>
  </template>
  <style>

body {
  background-image: url('https://img.freepik.com/free-vector/hand-drawn-fast-food-background_23-2149013389.jpg?w=2000');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  font-family: Andale Mono, monospace;
}


.center {
  margin: 0 auto;
}
h1 {
  font-family: Andale Mono, monospace;
}

</style>
