<template>
  <div id="app">
    <header-view />
    <router-view></router-view>
  </div>
</template>

<script>
import headerView from './components/headerView'
export default {
  name: 'app',
  components: {
    headerView
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
