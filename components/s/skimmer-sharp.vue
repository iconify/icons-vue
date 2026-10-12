<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ru9si1bxx"/><path class="ci2lgptiq"/><path class="t5tekyfbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skimmer-sharp" /></template>
<style>
.ci2lgptiq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 13.5h.01m3.99 0h.01m-4.01 3h.01m3.99 0h.01");
}

.ru9si1bxx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15a6.5 4.25 0 1 0 13 0a6.5 4.25 0 1 0-13 0Z");
}

.t5tekyfbb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.23 12.27l6.52-8.02");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
