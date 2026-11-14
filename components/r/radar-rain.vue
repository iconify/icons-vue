<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ln58nvb8e"/><path class="mxxzpfg0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radar-rain" /></template>
<style>
.ln58nvb8e {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm8.5-1L5.25 5.25");
}

.mxxzpfg0l {
  d: path("M15.25 12.5c1.75-.5 3 1 2.25 2.75c-.5 1.5-2.25 2.5-3.75 1.75c-1.5-1-.5-4 1.5-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
