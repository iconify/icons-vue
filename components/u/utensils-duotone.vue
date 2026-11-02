<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fiqd0pb0m"/><path class="d2ji6v-al"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:utensils-duotone" /></template>
<style>
.d2ji6v-al {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14V3a5 5 0 0 0-5 5v4a2 2 0 0 0 2 2zm0 0v7M3 3v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V3M7 3v18");
}

.fiqd0pb0m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 14h-3a2 2 0 0 1-2-2V8a5 5 0 0 1 5-5Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
