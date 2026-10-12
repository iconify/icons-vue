<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i821mw_vy"/><path class="g_2kelbcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moose-sharp" /></template>
<style>
.g_2kelbcc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 12h.01m2.99 0h.01m-2.76 6h.01m2.49 0h.01");
}

.i821mw_vy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 9.5h6q.75 3 .75 6l.35 1.75l.563 3H7.338l.562-3l.35-1.75q0-3 .75-6ZM7.5 7.75H5.25L3.5 6l-.77-.77L3 3.25l1.5 1L5.5 3l1 1.25l1.25-1L8.5 4.5l1-.5v2.95zm9 0h2.25L20.5 6l.77-.77L21 3.25l-1.5 1l-1-1.25l-1 1.25l-1.25-1l-.75 1.25l-1-.5v2.95z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
