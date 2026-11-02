<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xymm8zhht"/><path class="hj_9i6bjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:speedboat-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hj_9i6bjp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 17l-1-3h13l5-2l-1 5M5 14V9a2 2 0 0 1 2-2h2l7 7M9 7v7m-7 6c.5.5 1 1 2 1c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2c1 0 1.5-.5 2-1");
}

.xymm8zhht {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 9a3 3 0 0 1 3-3h2c.265 0 .52.105.707.293l7 7A1 1 0 0 1 16 15H5a1 1 0 0 1-1-1Z");
}

</style>
