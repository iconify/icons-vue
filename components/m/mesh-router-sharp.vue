<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k61wm1bdx"/><path class="gxbuc2gda"/><path class="gymv3qh9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mesh-router-sharp" /></template>
<style>
.gxbuc2gda {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 17.25h.01m10.99 0h.01");
}

.gymv3qh9p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 7.5L12 5.612L14.25 7.5m-6.5-2.75a6.5 6.5 0 0 1 8.5 0");
}

.k61wm1bdx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.25h6.5v12h-6.5zm11 0h6.5v12h-6.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
