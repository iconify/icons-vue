<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xn65p_m1f"/><path class="vqq0u1buh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.vqq0u1buh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2ZM3 18a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm12 0a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2ZM12 8v4m-6 4a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4");
}

.xn65p_m1f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 2h2a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3M5 15h2a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3m12 0h2a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3");
}

</style>
