<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jecngpyqf"/><path class="h-l279zrs"/><path class="mdm6x968z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recycle-cardboard" /></template>
<style>
.h-l279zrs {
  d: path("M15.25 6.75L17 8.5l1.75-1.75m-2.92 4.464A5 5 0 0 1 7 8");
}

.jecngpyqf {
  d: path("M3 16h18v5.5H3Zm9 0v5.5M8.25 4.75A5 5 0 0 1 17 8");
}

.mdm6x968z {
  d: path("M5.25 9.25L7 7.5l1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
