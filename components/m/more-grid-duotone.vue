<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d45drvnxw"/><path class="zbgw8rbqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-grid-duotone" /></template>
<style>
.d45drvnxw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 7a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2M6 13a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2M6 19a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

.ft5dv1b6b {
  fill: none;
}

.zbgw8rbqx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M5 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M5 18a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
