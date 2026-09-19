<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 24 24)" class="bma4tqtkq"/><path class="aa7tjib5b"/><rect class="jhy659bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:word-search" /></template>
<style>
.aa7tjib5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9 19.49V35c0 2.21 1.79 4 4 4h15.51M19.49 9H35c2.21 0 4 1.79 4 4v15.51m-13.77 3.265v-7.5h2.455c1.388 0 2.514 1.127 2.514 2.518s-1.126 2.52-2.514 2.52H25.23m2.455-.001l2.455 2.461M16.5 9.824l-1.875 7.5l-1.875-7.5l-1.875 7.5L9 9.824M33.71 39v-7.5h1.687a3.28 3.28 0 0 1 3.281 3.281v.938A3.28 3.28 0 0 1 35.398 39z");
}

.bma4tqtkq {
  width: 14.836px;
  height: 46.181px;
  x: 16.582px;
  y: 0.91px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.418px;
  ry: 7.418px;
}

.jhy659bcz {
  width: 4.969px;
  height: 7.5px;
  x: 17.654px;
  y: 16.775px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.484px;
  ry: 2.484px;
}

</style>
