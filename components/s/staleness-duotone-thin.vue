<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="txx5uqbdb"/><path class="sl0tqnboi"/><path class="yf0ac-1wm"/><path class="wuu7accch"/><path class="ennto9b9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staleness-duotone-thin" /></template>
<style>
.ennto9b9x {
  d: path("M16 16h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sl0tqnboi {
  d: path("M4 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.txx5uqbdb {
  fill: currentColor;
  d: path("M4 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wuu7accch {
  d: path("M14 20h7");
}

.yf0ac-1wm {
  d: path("M10 9v3h3");
}

</style>
