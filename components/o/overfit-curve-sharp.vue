<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="m927b1cms"/><path class="rlfoe5b5d"/><path class="r-x5n_oxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:overfit-curve-sharp" /></template>
<style>
.m927b1cms {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25v17.5h17.5");
}

.r-x5n_oxz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 17.5h.01m3.74-10.25h.01m3.99 9.5h.01m4.24-11.5h.01");
}

.rlfoe5b5d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 15.75C7.5 11.5 8.5 9 10.25 9s2.25 6 4 6s2.25-8 4.25-8");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
