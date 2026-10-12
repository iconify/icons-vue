<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dvna8tbyr"/><path class="ba-m2ubid"/><path class="oyi34fbpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:octopus-marine-sharp" /></template>
<style>
.ba-m2ubid {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 9.5h.01m4.99 0h.01");
}

.dvna8tbyr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 12.5c-.5-4.5 2-8.75 6.75-8.75S19.25 8 18.75 12.5Z");
}

.oyi34fbpj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12.5v4.25H3.5m6.75-4.25v4.7l-2 .8m5.5-5.5v4.7l2 .8M17 12.5v4.25h3.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
