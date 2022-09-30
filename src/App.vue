<template>
  <div class="bg-cyan-200 w-100 h-100">
    <img alt="Vue logo" src="./assets/logo.png">
    <HomePage msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    HomePage,
  },
};
</script>
