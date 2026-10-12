<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="lo_lt5b5d"/><rect class="gi1403bti"/><path class="qjvyleyug"/><path class="knl2yx9sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:microwave-clock" /></template>
<style>
.gi1403bti {
  width: 9px;
  height: 8.5px;
  x: 5.75px;
  y: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.knl2yx9sp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 15.75h1.5");
}

.lo_lt5b5d {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.qjvyleyug {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 8.75h.01M18 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
