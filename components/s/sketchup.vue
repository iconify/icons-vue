<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oj1ry2bel"/><path class="m3viprbpg"/><path class="fxw6n8d0z"/><path class="f2znrrbvt"/><path class="xdk-8pi3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sketchup" /></template>
<style>
.f2znrrbvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.589 15.873l6.204-3.582a12.41 12.41 0 0 1 12.412 0l6.206 3.583v7.166c0 4.434-2.366 8.532-6.206 10.749l-6.206 3.583");
}

.fxw6n8d0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.794 26.62L5.38 19.453l.002-7.165l12.41-7.165a12.41 12.41 0 0 1 12.414 0l12.412 7.164l.001 14.331c0 4.436-2.365 8.536-6.207 10.754L24 44.54M5.38 26.726l6.298-3.637");
}

.m3viprbpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.793 33.786L5.38 26.619c0 4.436 2.365 8.535 6.207 10.754L24 44.54");
}

.oj1ry2bel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.381 12.288L24 23.04v21.5");
}

.xdk-8pi3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 15.874l6.206 3.583v7.166");
}

</style>
