<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><circle class="wysq1-5hd"/><path class="ozzveb0ym"/><path class="la4qjn1gv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radar-ping-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.la4qjn1gv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.23 16.77h.01");
}

.ozzveb0ym {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 12l6.54-6.54");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wysq1-5hd {
  cx: 12px;
  cy: 12px;
  r: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
