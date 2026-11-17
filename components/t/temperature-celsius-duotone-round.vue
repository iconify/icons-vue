<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w4g47zm6q"/><path class="n6rl6dblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:temperature-celsius-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n6rl6dblm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 8a3 3 0 0 0-3-3h-2a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h2a3 3 0 0 0 3-3M3 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.w4g47zm6q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 7a2 2 0 1 1 3.999-.001A2 2 0 0 1 3 7");
}

</style>
