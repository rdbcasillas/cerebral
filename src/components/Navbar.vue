<template>
  <!-- <b-navbar>
    <template slot="brand">
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <img
          src="@/assets/images/branding.png"
          alt="Lightweight UI components for Vue.js based on Bulma"
        />
      </b-navbar-item>
    </template>
    <template slot="start">
      <b-navbar-item to="/about" tag="router-link">
        About
      </b-navbar-item>
    </template>

    <template slot="end"> </template>
  </b-navbar> -->

<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://bulma.io">
      <img src="../assets/images/thinkingman.jpg" width="50" height="38">
    </a>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item" href="/">
        Home
      </a>
      <a class="navbar-item" href="/about">
        About
      </a>
    </div>
  </div>
</nav>
</template>
<style lang="css" scoped>
.navbar {
  background: steelblue;
  font-weight: bold;
}
.navbar-item {
  color: aliceblue;
}
</style>
