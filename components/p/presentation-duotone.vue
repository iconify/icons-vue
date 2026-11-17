<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s53dw6bhx"/><path class="ui6j-ib1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:presentation-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s53dw6bhx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 3v11a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V3Z");
}

.ui6j-ib1k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3v11a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3M3 3h18m-9 13l-5 5m5-5l5 5");
}

</style>
