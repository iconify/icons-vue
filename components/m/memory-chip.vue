<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="csqoxtdvm"/><path class="zpx704bgk"/><rect class="a-hfhkb3o"/><path class="v4wrbvc_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:memory-chip" /></template>
<style>
.a-hfhkb3o {
  width: 3px;
  height: 4px;
  x: 10.5px;
  y: 8.75px;
  rx: 0.75px;
}

.csqoxtdvm {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 5.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4wrbvc_j {
  d: path("M6 15.75v2.5m3-2.5v2.5m6-2.5v2.5m3-2.5v2.5");
}

.zpx704bgk {
  d: path("M6.25 8.75h1A.75.75 0 0 1 8 9.5V12a.75.75 0 0 1-.75.75h-1A.75.75 0 0 1 5.5 12V9.5a.75.75 0 0 1 .75-.75m10.5 0h1a.75.75 0 0 1 .75.75V12a.75.75 0 0 1-.75.75h-1A.75.75 0 0 1 16 12V9.5a.75.75 0 0 1 .75-.75");
}

</style>
