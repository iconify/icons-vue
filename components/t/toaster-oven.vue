<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="mdr8e-bxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toaster-oven" /></template>
<style>
.hn7tnnbwb {
  d: path("M2.5 5h19v14h-19Z");
}

.mdr8e-bxh {
  d: path("M5.5 7.75H15v5.5H5.5Zm0 8.25H15m3.5-6.5h.01M18.5 13h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
