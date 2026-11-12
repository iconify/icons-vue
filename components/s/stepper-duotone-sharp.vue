<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xgnpp0w2f"/><path class="ulo4e4w4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stepper-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ulo4e4w4v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v8H3Zm4 4h10M3 18h6m6 0h6m-3-3v6");
}

.xgnpp0w2f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 11V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

</style>
