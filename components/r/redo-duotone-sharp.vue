<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nbjrp86wk"/><path class="hmpfzvb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:redo-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hmpfzvb9y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 15a7.616 7.616 0 1 1 0-6m-6 0h6V3");
}

.nbjrp86wk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4.384 12a7.617 7.617 0 1 1 15.233 0a7.617 7.617 0 1 1-15.233 0");
}

</style>
