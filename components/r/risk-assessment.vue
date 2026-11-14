<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ju3uevlhn"/><path class="toiidtbvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:risk-assessment" /></template>
<style>
.ju3uevlhn {
  d: path("M3 3h18v18H3Zm6 0v18m6-18v18M3 9h18M3 15h18");
}

.toiidtbvq {
  fill: currentColor;
  d: path("M15 3h4c1.1 0 2 .9 2 2v4h-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
