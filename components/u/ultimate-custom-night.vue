<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="i_i2og64y"/><path class="gqzjv8bro"/><circle class="mviq8kz1e"/><path class="haydp8b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ultimate-custom-night" /></template>
<style>
.gqzjv8bro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.264 42.5c.168-4.199 1.159-9.495 1.159-9.495");
}

.haydp8b2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.892 36.276c3.073 1.31 15.294.735 15.294.735");
}

.i_i2og64y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 18.213c-4.787-6.309-6.076-10.638-18.5-8.16c-8.584 1.713-11.293 12.702-10.272 16.823s9.77 7.57 9.77 7.57M42.5 32.371s-3.133 2.271-7.507 2.986c.21 2.23 1.01 7.143 1.01 7.143");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mviq8kz1e {
  cx: 28.474px;
  cy: 23.708px;
  r: 3.07px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
