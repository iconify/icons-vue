<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r_7j5cv3i"/><path class="djulzlbey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-duotone" /></template>
<style>
.djulzlbey {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H7a2 2 0 0 1-2-2V7c0-.64.36-1.36 1-2l1-1c.64-.64 1.36-1 2-1h6c.64 0 1.36.36 2 1l1 1c.64.64 1 1.36 1 2v8a2 2 0 0 1-2 2zm-4 0l-2 4m10-4l2 4M5 10h14M9 14h.01M15 14h.01");
}

.ft5dv1b6b {
  fill: none;
}

.r_7j5cv3i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 17H7a2 2 0 0 1-2-2V7c0-.763.48-1.479 1-2l1-1c.521-.52 1.237-1 2-1h6c.763 0 1.479.48 2 1l1 1c.52.521 1 1.237 1 2v8a2 2 0 0 1-2 2");
}

</style>
