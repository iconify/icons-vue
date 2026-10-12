<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="lot8r087d"/><path class="a4-ndobqs"/><path class="hdgtvjeta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whale" /></template>
<style>
.a4-ndobqs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14h.01");
}

.hdgtvjeta {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 17c2.25.75 5.25.75 8.25-.5");
}

.lot8r087d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13a2.5 2.5 0 0 1 2.5-2.5H12c2.5 0 4 1.25 5.25 3l1.5-3c-1-.5-1.5-1.5-1.5-2.75c1 0 2 .5 2.75 1.25c.25-1 1-1.75 1.25-1.75v3.5c0 .75-.5 1.25-1.25 1.75L19 16c-1.5 3-4.5 4.75-8 4.75c-4.5 0-7.75-3.25-7.75-7.75M7.5 7.5c0-1.5-.75-2.75-2-3.75m2 3.75c0-1.5.75-2.75 2-3.75m-2 3.75V3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
