<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ky5v2k6ae"/><path class="f8lmhfbaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ruler-duotone" /></template>
<style>
.f8lmhfbaq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 9l5-5a1.414 1.414 0 0 1 2 0l4 4a1.414 1.414 0 0 1 0 2L10 20a1.414 1.414 0 0 1-2 0l-4-4a1.414 1.414 0 0 1 0-2zm-4 4l2 2m2-6l2 2m2-6l2 2");
}

.ft5dv1b6b {
  fill: none;
}

.ky5v2k6ae {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.293 3.293a2.414 2.414 0 0 1 3.414 0l4 4a2.414 2.414 0 0 1 0 3.414l-10 10a2.414 2.414 0 0 1-3.414 0l-4-4a2.414 2.414 0 0 1 0-3.414Z");
}

</style>
