<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jb4hv68nd"/><path class="r0ppflb1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jb4hv68nd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 2h10c.265 0 .52.105.707.293l4 4A1 1 0 0 1 20 7v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

.r0ppflb1t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3h10l4 4v14H5zm4 6h6v8H9Zm0 4h6");
}

</style>
