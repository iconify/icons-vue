<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ale7s0uzc"/><path class="jisbgab1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-basket-duotone-round" /></template>
<style>
.ale7s0uzc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 9h16a1 1 0 0 1 .962 1.275l-2 7c-.396 1.384-1.262 2.775-2.602 3.41A3.2 3.2 0 0 1 15 21H9a3.2 3.2 0 0 1-1.36-.315c-1.34-.635-2.206-2.026-2.602-3.41l-2-7A1 1 0 0 1 4 9");
}

.ft5dv1b6b {
  fill: none;
}

.jisbgab1t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10h18M4 10l2 7c.507 1.776 1.732 3 3 3h6c1.268 0 2.493-1.224 3-3l2-7m-10 0v10m4-10v10M5 10l4-6m10 6l-4-6");
}

</style>
