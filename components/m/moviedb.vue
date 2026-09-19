<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x0vyzjbvo"/><path class="a_15_cc2o"/><rect class="vrz9hdb4y"/><path class="i5771hx5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moviedb" /></template>
<style>
.a_15_cc2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.07 23.55l-8.07 6v.58a2.47 2.47 0 0 0 2.48 2.47h23.93a2.46 2.46 0 0 0 2.47-2.47V26a2.47 2.47 0 0 0-2.47-2.48Z");
}

.i5771hx5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.2 26.32c0-4.48 0-10.81-.07-14a54 54 0 0 1 0-5.84l9.61 7l9.58 7s-16.84 12.38-19 13.93c-.09.06-.09-.42-.12-8.09");
}

.vrz9hdb4y {
  width: 28.88px;
  height: 9.01px;
  x: 13px;
  y: 32.56px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.48px;
}

.x0vyzjbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.07 23.55h18.34a2.46 2.46 0 0 0 2.47-2.47V17a2.47 2.47 0 0 0-2.47-2.48h-22");
}

</style>
