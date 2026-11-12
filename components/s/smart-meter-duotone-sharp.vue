<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g6q41s4ti"/><path class="hwbf8s1jv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smart-meter-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g6q41s4ti {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 21V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

.hwbf8s1jv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v17H3Zm5-1v1m8-1v1M6 7h12v5H6Zm4 0v5m4-5v5m-5 4c1-1.333 5-1.333 6 0m-3 2h.01");
}

</style>
