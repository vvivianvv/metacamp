<template>
  <div>
    <app-header />
    <router-view />
  </div>
</template>

<script>
import Header from './components/layout/Header.vue'
export default {
  components: {
    'app-header': Header
  }
}
</script>

<style src="./assets/style/main.css"></style>
