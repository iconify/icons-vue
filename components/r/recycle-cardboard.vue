<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e-b4mggwu"/><path class="h-l279zrs"/><path class="mdm6x968z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recycle-cardboard" /></template>
<style>
.e-b4mggwu {
  d: path("M5.625 16h12.75A2.625 2.625 0 0 1 21 18.625v.25a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-.25A2.625 2.625 0 0 1 5.625 16M12 16v5.5M8.25 4.75A5 5 0 0 1 17 8");
}

.h-l279zrs {
  d: path("M15.25 6.75L17 8.5l1.75-1.75m-2.92 4.464A5 5 0 0 1 7 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mdm6x968z {
  d: path("M5.25 9.25L7 7.5l1.75 1.75");
}

</style>
