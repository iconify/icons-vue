<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="y37uk-bwf"/><path class="m7hlo1bxu"/><path class="zh70awb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:password-check-sharp" /></template>
<style>
.m7hlo1bxu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12h.01m3.49 0h.01M14 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y37uk-bwf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75h18.5v10.5H2.75z");
}

.zh70awb4u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 9.75v4.5");
}

</style>
