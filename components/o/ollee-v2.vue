<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="c i-f81ybtw"/><path class="r r_xel2bvj"/><circle class="r wl84albbe" transform="scale(-1 1)"/><path class="r t0z2xbsbn"/><circle class="r uiixi0biz" transform="scale(-1 1)"/><path class="iwt1zac5z r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ollee-v2" /></template>
<style>
.i-f81ybtw {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  rx: 4px;
  ry: 4px;
}

.iwt1zac5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.645 27.677c-.537.703-1.355 1.186-2.71 1.186h-.227a3.22 3.22 0 0 1-3.221-3.221v-3.283");
}

.r_xel2bvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.56 24.85a2.431 2.431 0 1 1 4.863 0v1.581a2.431 2.431 0 1 1-4.862 0zm10.703-4.388l2.431-1.324v9.725m-6.929-8.401l2.431-1.324v9.725");
}

.t0z2xbsbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.154 27.677c-.536.703-1.354 1.186-2.71 1.186h-.226a3.22 3.22 0 0 1-3.222-3.221v-3.283");
}

.uiixi0biz {
  cx: -27.708px;
  cy: 22.359px;
  r: 3.221px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wl84albbe {
  cx: -36.218px;
  cy: 22.359px;
  r: 3.221px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
