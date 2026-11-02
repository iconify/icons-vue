<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kwm82p41q"/><path class="sbtvxobot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swatches-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kwm82p41q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 7a5 5 0 0 1 10 0v10a5 5 0 0 1-10 0Z");
}

.sbtvxobot {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V7a4 4 0 1 1 8 0v10a4 4 0 1 1-8 0m4 0h.01M11 9l2-2a2.83 2.83 0 0 1 4 0l1 1a2.83 2.83 0 0 1 0 4l-9 9m7-7h2a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H7");
}

</style>
