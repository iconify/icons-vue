<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hrvg60ypl"/><path class="j8fhg9bqz"/><path class="r9na1kb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rinse-cycle" /></template>
<style>
.hrvg60ypl {
  d: path("M3.5 2h17v20h-17Z");
}

.j8fhg9bqz {
  d: path("M6 12.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.r9na1kb0p {
  d: path("M9 10.75q1.5-1 3 0t3 0m-6 3.5q1.5-1 3 0t3 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
