<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sc6ygbc0b"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rhombus-sharp" /></template>
<style>
.sc6ygbc0b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.35 3.97l6.05 6.56L20.75 12l-1.35 1.47l-6.05 6.56L12 21.5l-1.35-1.47l-6.05-6.56L3.25 12l1.35-1.47l6.05-6.56L12 2.5z");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
