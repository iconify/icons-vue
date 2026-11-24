<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s1b77fbel"/><path class="tdt41ub6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:town-hall-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s1b77fbel {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 8a5 5 0 0 1 10 0v7h2a2 2 0 0 1 2 2v4H3v-4a2 2 0 0 1 2-2h2Z");
}

.tdt41ub6b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 8v7h2a2 2 0 0 1 2 2v4H3v-4a2 2 0 0 1 2-2h2V8m3 13v-2a2 2 0 1 1 4 0v2M7 8a5 5 0 0 1 10 0m0 0A5 5 0 0 1 7 8m5-2v2h2");
}

</style>
