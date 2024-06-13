<template>
  <div id="app">
    <HeaderComponent />
    <ContentComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import ContentComponent from './components/ContentComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    ContentComponent
  }
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
