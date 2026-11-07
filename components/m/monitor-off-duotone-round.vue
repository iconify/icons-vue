<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tx_02kblg"/><path class="l2a3svw1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l2a3svw1s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.647 16.647A4 4 0 0 1 16 17H8a4 4 0 0 1-4-4V8c0-1.36.679-2.561 1.716-3.284M11 4h5a4 4 0 0 1 4 4v5M9 20h6M3 2l19 19");
}

.tx_02kblg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 4h5a4 4 0 0 1 4 4v5Zm6.646 12.646A4 4 0 0 1 16 17H8a4 4 0 0 1-4-4V8c0-1.313.636-2.537 1.716-3.284Z");
}

</style>
