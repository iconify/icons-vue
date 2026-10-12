<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="wfdnybbtq"/><path class="uh7kh3hji"/><circle class="h0bt1kb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shocked-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.h0bt1kb7e {
  cx: 12px;
  cy: 15.5px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uh7kh3hji {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.75 7l1-.75l1 .75m4.5 0l1-.75l1 .75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wfdnybbtq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10h.01M15 10h.01");
}

</style>
