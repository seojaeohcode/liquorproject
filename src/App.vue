<template>
  <nav>
    <b-nav tabs align="center">
      <b-nav-item><router-link to="/">Main</router-link></b-nav-item>
      <b-nav-item><router-link to="/about">DrinkIntro</router-link> </b-nav-item>
      <b-nav-item><router-link to="/kind">Kind</router-link></b-nav-item>
      <b-nav-item><router-link to="/region">region</router-link></b-nav-item>
    </b-nav>
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
