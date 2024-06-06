<!-- <script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div id="app">
  <nav>
  <ul>
  <li><router-link to="/">Home</router-link></li>
  <li><router-link to="/about">About</router-link></li>
  <li><router-link to="/services">Services</routerlink></li>
  </ul>
  </nav>
  <router-view/>
  </div>
  </template>
  <script>
  export default {
  name: 'App'
  }
  </script>
  <style>
  nav ul {
  list-style-type: none;
  padding: 0;
  }
  nav ul li {
  display: inline;
  margin-right: 10px;
  }
  </style> -->

<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div id="app">
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
        <li><router-link to="/services">Services</router-link></li>
      </ul>
    </nav>
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
<style>
nav ul {
  list-style-type: none;
  padding: 0;
}
nav ul li {
  display: inline;
  margin-right: 10px;
}
</style>
