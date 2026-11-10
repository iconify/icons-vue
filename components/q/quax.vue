<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gs77v-1pa"/><path class="quv3ddbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quax" /></template>
<style>
.gs77v-1pa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.508 39.614c-9.383 3.48-19.81-1.306-23.29-10.69c-3.479-9.382 1.307-19.81 10.69-23.289s19.81 1.307 23.29 10.69a18.12 18.12 0 0 1-3.04 17.863");
}

.quv3ddbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.216 4.502c-4.803.002-8.696 8.117-8.695 18.124c0 10.004 3.893 18.113 8.695 18.116m2.356-8.698L42.917 43.5");
}

</style>
