<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rp-42eqth"/><path class="ee1adkbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:zinnia" /></template>
<style>
.ee1adkbsb {
  d: path("M9.75 9.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm2.25 11c1.5-2 4-2.5 6.5-2c-1.5 2-4 2.75-6.5 2Z");
}

.rp-42eqth {
  d: path("M17.75 9.5a2.25 2.25 0 0 1-1.75 4a2.25 2.25 0 0 1-4 1.75a2.25 2.25 0 0 1-4-1.75a2.25 2.25 0 0 1-1.75-4A2.25 2.25 0 0 1 8 5.5a2.25 2.25 0 0 1 4-1.75a2.25 2.25 0 0 1 4 1.75a2.25 2.25 0 0 1 1.75 4ZM12 15.25v6.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
