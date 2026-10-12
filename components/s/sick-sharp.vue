<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="ljj8te3xk"/><path class="wfdnybbtq"/><path class="jpztalbxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sick-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpztalbxi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 13.25l-3.75-2m13.25 2l3.75-2m-13.25 1.5h9.5v4.75h-9.5v-2.75Zm2 2.5h5.5");
}

.ljj8te3xk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 7.75l1.625-.542L10 7.5m6.5.25l-1.625-.542L14 7.5");
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
