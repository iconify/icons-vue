<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pt2ig43ia"/><path class="ur8fgibmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-low-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt2ig43ia {
  stroke-opacity: 0.4;
  d: path("M14 20h.01M18 20h.01");
}

.ur8fgibmh {
  d: path("M6 20v-4m4 4v-8");
}

</style>
