<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o9zqzop1y"/><path class="w9a6t4fsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-play-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o9zqzop1y {
  stroke-opacity: 0.4;
  d: path("m11.573 8.101l2.257 1.58a1 1 0 0 1 0 1.638l-2.257 1.58a1 1 0 0 1-1.573-.82V8.921a1 1 0 0 1 1.573-.82");
}

.w9a6t4fsv {
  d: path("M4 8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v5a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm5 12h6");
}

</style>
