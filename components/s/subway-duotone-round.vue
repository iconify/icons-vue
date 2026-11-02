<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xugpblzjp"/><path class="m-0gpfn4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subway-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m-0gpfn4y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12a5 5 0 0 1 10 0v5a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm3 7l-1 2m5-2l1 2m-8-9h10M3 21v-9a9 9 0 0 1 18 0v9m-11-6h.01M14 15h.01");
}

.xugpblzjp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 12v5a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-5a6 6 0 1 1 12 0");
}

</style>
