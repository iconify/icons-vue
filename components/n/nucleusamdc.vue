<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ko5dj0brk"/><path class="b48odx5ro"/><path class="s2azjxoyw"/><path class="h4ic3rb2p"/><path class="i0e2apbti"/><path class="i8mupdu5r"/><path class="tgc78ac8g"/><path class="zdj9c0y2c"/><path class="apvdypfkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nucleusamdc" /></template>
<style>
.apvdypfkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.931 30.307a5.857 5.857 0 0 1 .676-10.92m4.881-10.091a5.857 5.857 0 0 1 8.279-3.71m-7.182 15.337a5.86 5.86 0 0 1 1.475 5.386m16.262 2.617a5.86 5.86 0 0 1 .753-2.917");
}

.b48odx5ro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.169 17.551a5.857 5.857 0 1 1 .46-1.785m3.004-3.098a5.857 5.857 0 1 1 7.429 1.939m.054.384a5.857 5.857 0 1 1-3.146 8.82");
}

.h4ic3rb2p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.306 10.374a5.857 5.857 0 0 1 9.501 6.127m1.751 10.064a5.857 5.857 0 0 1-4.305 8.074");
}

.i0e2apbti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.444 34.55a5.857 5.857 0 1 1 1.563 4.174");
}

.i8mupdu5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.603 33.373a5.857 5.857 0 1 1-8.329 4.283");
}

.ko5dj0brk {
  cx: 23.024px;
  cy: 18.143px;
  r: 5.857px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s2azjxoyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.03 17.437a5.857 5.857 0 1 1-1.374 7.683");
}

.tgc78ac8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.42 23.993a5.857 5.857 0 1 1-1.664-.444");
}

.zdj9c0y2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.527 34.978a5.857 5.857 0 1 1-3.342-6.565");
}

</style>
