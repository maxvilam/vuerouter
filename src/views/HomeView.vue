<template>
  <div class="home">
    <HelloWorld msg="Bienvenido a VueRouter y Firebase" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
