<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><circle class="f73ungbos"/><path class="asf_7zb_n"/><path class="eu42wt9jy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:post-image" /></template>
<style>
.aqmj_4big {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.asf_7zb_n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 7H17M2.75 10.5h18.5m-15 7.25L9.75 14l2.75 2.75L14.25 15l3.25 2.75");
}

.eu42wt9jy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 13.5h.01");
}

.f73ungbos {
  cx: 7px;
  cy: 7px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
