<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ynda_kb6k"/><path class="lj49l8biv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vulnerable-package" /></template>
<style>
.lj49l8biv {
  d: path("M3.5 6L10 9.5L16.5 6M10 9.5v7m8-1.75v3.5M18 21h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ynda_kb6k {
  d: path("M10 2.5L16.5 6v7L10 16.5L3.5 13V6Z");
}

</style>
