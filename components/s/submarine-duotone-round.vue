<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="situ8-b_s"/><path class="ib4m_9-3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:submarine-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ib4m_9-3t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 20h-7a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3V9a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3h3a4 4 0 1 1 0 8M3 12v8m0-4h4m5-8V6a2 2 0 0 1 2-2h2m-4 12h.01M16 16h.01");
}

.situ8-b_s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 21a4 4 0 0 1-4-4v-2a4.006 4.006 0 0 1 3-3.874V9a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2h2a5 5 0 0 1 0 10Z");
}

</style>
