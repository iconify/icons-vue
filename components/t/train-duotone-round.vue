<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ovhrfxbtz"/><path class="o0ul6jb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o0ul6jb4v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H7a2 2 0 0 1-2-2V8c0-1.28.36-2.36 1-3l1-1c.64-.64 1.72-1 3-1h4c1.28 0 2.36.36 3 1l1 1c.64.64 1 1.72 1 3v7a2 2 0 0 1-2 2zm-4 0l-2 4m10-4l2 4M5 10h14M9 14h.01M15 14h.01");
}

.ovhrfxbtz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 17H7a2 2 0 0 1-2-2V8c0-1.041.237-2.236 1-3l1-1c.764-.763 1.959-1 3-1h4c1.041 0 2.236.237 3 1l1 1c.763.764 1 1.959 1 3v7a2 2 0 0 1-2 2");
}

</style>
