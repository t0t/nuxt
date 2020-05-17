<template>
  <div>
  <Navigation />
  <div class="page-transition">
    <nuxt />
  </div>
  </div>
</template>

<script>
import Navigation from "../components/Navigation";
export default {
  head() {
    return {
      // link: [
      //   {
      //     rel: "stylesheet",
      //     href: "https://fonts.googleapis.com/css?family=Oswald&display=swap"
      //   }
      // ]
    };
  },
  components: {
    Navigation
  }
};
</script>

<style lang="scss">
@import "../assets/styles/main.scss";


</style>
