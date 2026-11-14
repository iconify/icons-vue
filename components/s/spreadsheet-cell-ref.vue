<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c8xs3w9gw"/><path class="i5uunab7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spreadsheet-cell-ref" /></template>
<style>
.c8xs3w9gw {
  d: path("M3 3h18v18H3Zm0 6h18M9 3v18");
}

.i5uunab7g {
  fill: currentColor;
  d: path("M12 12h6v6h-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
