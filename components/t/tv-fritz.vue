<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jhoq5qb0d"/><path class="qwkwe9brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tv-fritz" /></template>
<style>
.jhoq5qb0d {
  width: 37.008px;
  height: 25.233px;
  x: 5.496px;
  y: 9.444px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.682px;
}

.qwkwe9brd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.1 38.556h17.8M23.46 18.1v7.92M10 18.1h3.96M10 22.06h2.57M10 18.1v7.92m6.08 0V18.1h2.59a2.66 2.66 0 0 1 0 5.32h-2.59m2.59 0l2.59 2.6m4.35-7.92h5.24m-2.62 7.92V18.1m4.53 0H38l-5.24 7.92H38");
}

</style>
