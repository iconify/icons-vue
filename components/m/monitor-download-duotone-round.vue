<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p9xuj-2zq"/><path class="qf3fdmtif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-download-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p9xuj-2zq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v5a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Z");
}

.qf3fdmtif {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v5a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm5 12h6m-6-9l3 3l3-3m-3 3V7");
}

</style>
