<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a-q_5yh_o"/><path class="m7-y_v0cd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webcam-duotone-sharp" /></template>
<style>
.a-q_5yh_o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 17a7 7 0 1 1 0-14a7 7 0 0 1 0 14M9.202 8.916a3 3 0 1 0 1.205-1.46a.02.02 0 0 0 .002-.027a.02.02 0 0 0-.027-.004c-.521.323-.93.799-1.171 1.363a2.97 2.97 0 0 0-.218 1.671c.005.027.009.137.044.131a.02.02 0 0 0 .016-.024a2.9 2.9 0 0 1 .149-1.65M11 10a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

.ft5dv1b6b {
  fill: none;
}

.m7-y_v0cd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 10a7 7 0 1 0 14 0a7 7 0 0 0-14 0m4 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3 7v4m-4 0h8");
}

</style>
