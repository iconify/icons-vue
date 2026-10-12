<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sfnjrmb_p"/><path class="ee3j9zb_t"/><path class="xznc7pb3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:star-tracker-sharp" /></template>
<style>
.ee3j9zb_t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.75q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25Z");
}

.sfnjrmb_p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0m6-9.25V6m0 12v3.25M2.75 12H6m12 0h3.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xznc7pb3q {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.5 4.5h.01m14.99 15h.01");
}

</style>
