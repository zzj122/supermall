<template>
  <div id="app">
    <router-view/>
    <main-tab-ber/>
  </div>
</template>

<script>
  import MainTabBer from 'components/content/mainTabbar/MainTabBar.vue'

export default {
  name: 'app',
  components: {
    MainTabBer
  }
}
</script>

<style>
  @import "assets/css/base.css"
</style>
