<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6_78abrt"/><path class="yspzyrbdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:step-over-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i6_78abrt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 19a2 2 0 1 1 3.999-.001A2 2 0 0 1 16 19");
}

.yspzyrbdj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11a7 7 0 0 1 14 0v2m-3-3l3 3l3-3m-5 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
