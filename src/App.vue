<template>
  <div id="app">
    <img src="./assets/logo.png">

    <div>

      <ul style="list-style: none;">
        <li style=" display: inline; margin-right:10px;  "><router-link to="/"> Home </router-link></li>
        <li style=" display: inline; margin-right:10px;"><router-link to="/firstroute/Ismail"> FirstRoute </router-link></li>
        <li style=" display: inline;margin-right:10px;"><router-link to="/firstroute/Ismail/child"> FirstRouteChild </router-link></li>


      </ul>

    

    </div>





    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
