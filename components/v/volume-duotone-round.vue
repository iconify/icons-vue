<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vpnrlhbmp"/><path class="t0pa24bda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.t0pa24bda {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 7v10c0 1.107-1.262 1.738-2 1l-1-1c-.64-.64-1.36-1-2-1H5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h1c.64 0 1.36-.36 2-1l1-1c.738-.738 2-.107 2 1");
}

.vpnrlhbmp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 17c0 1.107-1.262 1.738-2 1l-1-1c-.521-.52-1.237-1-2-1H5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h1c.763 0 1.479-.48 2-1l1-1c.738-.738 2-.107 2 1Z");
}

</style>
