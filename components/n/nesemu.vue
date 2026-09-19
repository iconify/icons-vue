<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="pr52f_b5y"><rect class="va3-rht_a"/><path class="jnhml946q"/><ellipse transform="rotate(-88.427 33.446 27.644)" class="a-bl1jx2m"/><ellipse transform="rotate(-88.427 38.781 27.644)" class="xf208q3rl"/><path class="xr_z64bjw"/><path class="nnkcfxb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nesemu" /></template>
<style>
.a-bl1jx2m {
  cx: 33.446px;
  cy: 27.644px;
  stroke-linejoin: round;
  rx: 1.677px;
  ry: 1.655px;
}

.jnhml946q {
  stroke-linejoin: round;
  d: path("M9.361 21.729v2.488h-2.48v2.554h2.48v2.489h2.549v-2.489h2.481v-2.554H11.91V21.73z");
}

.nnkcfxb2h {
  d: path("M18.048 23.18h10.797m-10.797-2.844h10.797m-10.797-2.845h10.797m-10.797 13.58h10.797");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.va3-rht_a {
  width: 41px;
  height: 17.662px;
  x: 3.5px;
  y: 15.169px;
  stroke-linejoin: round;
  rx: 1.109px;
  ry: 1.109px;
}

.xf208q3rl {
  cx: 38.781px;
  cy: 27.644px;
  stroke-linejoin: round;
  rx: 1.677px;
  ry: 1.655px;
}

.xr_z64bjw {
  stroke-linejoin: round;
  d: path("M20.137 27.31h1.854m2.91 0h1.854m-8.707-2.002h10.797v4.003H18.048z");
}

</style>
