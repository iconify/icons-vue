<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="w3y7wxbcs"/><path class="sch89tb6f"/><path class="nloarb2jk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:otter-sharp" /></template>
<style>
.nloarb2jk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.25q2.25-1.875 4.5 0c2.25 1.875 3 1.25 4.5 0s3-1.25 4.5 0s3 1.25 4.5 0");
}

.sch89tb6f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 9.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w3y7wxbcs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.5c1.5.75 2.5 0 4.25 0h7.01a3 3 0 1 1 5.59 1.25H21v1.75h-1.75c-.75.25-1 .75-2.25.75H4.25V12.5L3.5 11zm5.75 0l.75-2m2 2l.75-2");
}

</style>
