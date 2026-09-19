<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="yxlrir3lk"/><path class="v4ul-zb0j"/><circle class="hgc8bxbkt"/><path class="vicdo1bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sparkasse-mobile-payment" /></template>
<style>
.hgc8bxbkt {
  cx: 15.238px;
  cy: 23.302px;
  r: 3.092px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v4ul-zb0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.283 31.763h14.275M5.941 37.131h14.275");
}

.vicdo1bow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.825 18.896c.485-.546.788-1.257.788-2.045s-.303-1.498-.788-2.044m4.285 7.191c1.221-1.375 1.985-3.164 1.985-5.147s-.764-3.772-1.984-5.146M33.396 25.1c1.956-2.203 3.18-5.07 3.18-8.249s-1.224-6.046-3.18-8.249m4.286 19.601c2.691-3.032 4.377-6.979 4.377-11.352S40.373 8.531 37.682 5.5");
}

.yxlrir3lk {
  width: 18.617px;
  height: 16.106px;
  x: 5.941px;
  y: 26.394px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.092px;
  ry: 3.092px;
}

</style>
