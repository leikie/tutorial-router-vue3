<template>
  <div id="container">
    <nav>
      <router-link :to="{name: 'Home'}">Home</router-link> | 
      <router-link :to="{name: 'About'}">About</router-link> | 
      <router-link to="/user/baledemy">User</router-link> 
    </nav>

    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
