<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ef1z18cck"/><path class="e0lzhpbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medal-duotone-round" /></template>
<style>
.e0lzhpbfo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16a5 5 0 1 0 10 0a5 5 0 0 0-10 0m2-4L6 3h4l2 4l2-4h4l-3 9");
}

.ef1z18cck {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.162 11.678a6 6 0 1 1-8.324 0L5.051 3.316A1.002 1.002 0 0 1 6 2h4c.379 0 .725.214.894.553L12 4.764l1.106-2.211A1 1 0 0 1 14 2h4a1.002 1.002 0 0 1 .949 1.316Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
