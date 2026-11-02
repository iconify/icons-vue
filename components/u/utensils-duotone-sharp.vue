<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dd5ra1baq"/><path class="o7g6d7bei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:utensils-duotone-sharp" /></template>
<style>
.dd5ra1baq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 14h-5V8a5 5 0 0 1 5-5Z");
}

.ft5dv1b6b {
  fill: none;
}

.o7g6d7bei {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14V3a5 5 0 0 0-5 5v6zm0 0v7M3 3v8h8V3M7 3v18");
}

</style>
