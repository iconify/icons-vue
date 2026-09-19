<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="w72qx1e-d"/><path class="yguvyvbcm"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pepper-invest" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.w72qx1e-d {
  width: 1.5px;
  height: 1.5px;
  x: 38.212px;
  y: 38.108px;
  fill: currentColor;
  rx: 0.75px;
  ry: 0.75px;
}

.yguvyvbcm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.802 39.101h-3.25v-6.498h3.25m-3.25 3.249h2.112m2.814 2.518c.407.488.894.731 1.625.731h.975a1.63 1.63 0 0 0 1.625-1.624a1.63 1.63 0 0 0-1.625-1.625h-1.056a1.63 1.63 0 0 1-1.625-1.625a1.63 1.63 0 0 1 1.625-1.624h.975c.73 0 1.218.162 1.624.73m-10.965-.73L18.544 39.1l-2.112-6.498M10.231 39.1v-6.498l4.306 6.498v-6.498M35.51 39.1v-6.498m-2.112 0h4.225m-29.388 0V39.1");
}

</style>
