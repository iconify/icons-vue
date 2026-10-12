<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nd0ijgbar"/><path class="uvpb0bmgi"/><path class="bh8e4ub0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tram-sharp" /></template>
<style>
.bh8e4ub0k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.75 18.75l-1.25 2.5m7.75-2.5l1.25 2.5");
}

.nd0ijgbar {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 7.25h13.5v11.5H5.25zm3.25-4.5h7m-5.5 0l2 4.5l2-4.5M5.25 12.5h13.5");
}

.uvpb0bmgi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 15.5h.01m6.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
