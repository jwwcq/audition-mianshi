<template>
  <div class="app">
    <myTest v-if="show"></myTest>
  </div>
</template>
<script>
import myTest from "./components/v-model和.sync/index.vue";
export default {
  components: {
    myTest,
  },
  data() {
    return {
      show: true,
    };
  },
};
</script>
<style scoped>
.app {
  width: 900px;
}
</style>
