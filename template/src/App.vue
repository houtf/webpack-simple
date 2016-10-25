<template>
  <div id="app">
    <nav></nav>
  </div>
</template>

<script>
  import Nav from './components/Nav.vue'
  export default {
    components: {
      Nav
    },
    data () {
      return {
        baseURL : ''
      }
    }
  }
</script>
<style>
  @import 'assets/css/ress.min.css';
</style>