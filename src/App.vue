<template>
  <div>
    <HeaderView/>
    <router-view/>
    <FooterView/>
  </div>
</template>

<script>
 import HeaderView from './components/Header.vue'
 import FooterView from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    HeaderView,
    FooterView
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
