<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="dw-27foii"/><circle class="uzghwrcmy"/><path class="plxl54g9i"/><circle class="i19whesmo"/><path class="m3rq1nrto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:new-scientist" /></template>
<style>
.dw-27foii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.625 30.542c.389.505.876.693 1.553.693h.938a1.58 1.58 0 0 0 1.58-1.58v-.006a1.58 1.58 0 0 0-1.58-1.58h-1.034A1.58 1.58 0 0 1 8.5 26.488h0c0-.876.71-1.585 1.585-1.585h.932c.678 0 1.165.188 1.553.694m-4.07-2.5v-6.332l4.195 6.332v-6.332m11.079 2.137l-1.306 4.195l-1.306-4.195l-1.306 4.195l-1.306-4.195");
}

.i19whesmo {
  cx: 32.046px;
  cy: 25.101px;
  r: 0.75px;
  fill: currentColor;
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

.m3rq1nrto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.046 27.04v4.195m1.638-.354c.289.243.6.354 1.302.354h.355c.578 0 1.047-.47 1.047-1.049h0c0-.579-.47-1.048-1.047-1.048h-.71c-.578 0-1.047-.47-1.047-1.05h0c0-.579.469-1.048 1.047-1.048h.355c.7 0 1.013.111 1.302.354m-6.639-1.66v4.71c0 .437.354.792.791.792h.238m-1.861-4.196h1.663m7.99-1.306v4.71c0 .437.355.792.793.792h.237m-1.86-4.196h1.662m-22.24 3.398a1.58 1.58 0 0 1-1.375.797h0a1.583 1.583 0 0 1-1.583-1.583v-1.029c0-.874.708-1.583 1.583-1.583h0c.587 0 1.1.32 1.373.795m10.75 3.4v-2.612c0-.874-.709-1.583-1.583-1.583h0c-.875 0-1.583.709-1.583 1.583m0 2.612V27.04m-7.438-4.741a1.58 1.58 0 0 1-1.375.799h0a1.583 1.583 0 0 1-1.584-1.584v-1.029c0-.874.71-1.583 1.584-1.583h0c.874 0 1.583.709 1.583 1.583V21h-3.167m8.78 9.437a1.58 1.58 0 0 1-1.376.798h0a1.583 1.583 0 0 1-1.583-1.583v-1.029c0-.874.708-1.583 1.583-1.583h0c.874 0 1.583.709 1.583 1.583v.515h-3.166");
}

.plxl54g9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.55 27.04v4.195");
}

.uzghwrcmy {
  cx: 18.55px;
  cy: 25.101px;
  r: 0.75px;
  fill: currentColor;
}

</style>
