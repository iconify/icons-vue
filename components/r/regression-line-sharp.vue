<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="m927b1cms"/><path class="baywifgxn"/><path class="yx_9p-bpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:regression-line-sharp" /></template>
<style>
.baywifgxn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11h.01M13 8h.01m4.49-3h.01M11.5 17.75h.01M15.5 15h.01m3.99-2.5h.01");
}

.m927b1cms {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25v17.5h17.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yx_9p-bpi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 16.5l13.5-8");
}

</style>
