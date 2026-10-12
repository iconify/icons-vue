<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="km7bmwd7z"/><rect class="pj4t9bx_j"/><path class="mkd1vjboj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:max-tokens" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.km7bmwd7z {
  d: path("M3.75 4.25h16.5m-16.5-1.5v3m16.5-3v3");
}

.mkd1vjboj {
  d: path("M6.25 13h11.5m-11.5 4h11.5");
}

.pj4t9bx_j {
  width: 11.5px;
  height: 12.5px;
  x: 6.25px;
  y: 8.75px;
  rx: 2.5px;
}

</style>
