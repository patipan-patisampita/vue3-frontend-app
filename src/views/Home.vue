<template>
  <div class="home">
    <NavBar />

    <button class="btn btn-primary">OK</button>

    <img alt="Vue logo" src="../assets/logo.png" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" /> -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
// import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
// import NavBar from "../components/NavBar.vue";
import NavBar from "@/components/NavBar.vue";
export default defineComponent({
  name: "Home",
  components: {
    // HelloWorld,
    NavBar,
  },
});
</script>
