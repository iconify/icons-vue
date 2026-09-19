<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dvqyai_9l"/><path class="y9f0y9b1j"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixels" /></template>
<style>
.dvqyai_9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.91 33.993l-8.681-5.107l.092-10.054l8.772-4.947l8.68 5.106l-.092 10.054z");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.y9f0y9b1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.521 19.052l8.37 4.917l8.778-4.787m-8.779 4.892l-.001 9.902m.073.312v8.035m8.901-23.19l9.598-5.621m-27.336 5.534l-9.54-5.527");
}

</style>
