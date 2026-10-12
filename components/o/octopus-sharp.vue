<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rpf7tuu-e"/><path class="jjcr4pdah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:octopus-sharp" /></template>
<style>
.jjcr4pdah {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 10h.01m4.99 0h.01");
}

.rpf7tuu-e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 10.5a6.75 6.75 0 0 1 13.5 0V13l-1.5 1.5H6.75L5.25 13zm2 5.5l-.765 3.441l-3.235.809m7-4v3l-2 2m5.5-5v3l2 2m1-5.25l.765 3.441l3.235.809");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
