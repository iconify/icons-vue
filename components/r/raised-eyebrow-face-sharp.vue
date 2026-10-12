<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="dd_6j-l0z"/><path class="bwfmpe9es"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:raised-eyebrow-face-sharp" /></template>
<style>
.bwfmpe9es {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8.25h3m3-.25l1.406-2.344L16.75 7.5M9.5 15.75h5");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.dd_6j-l0z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h.01M15 11h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
