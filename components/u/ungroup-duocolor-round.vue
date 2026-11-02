<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="up950ccwj"/><path class="lf7_zrbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ungroup-duocolor-round" /></template>
<style>
.lf7_zrbyj {
  d: path("M8 5h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.up950ccwj {
  stroke-opacity: 0.4;
  d: path("M15 14h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2z");
}

</style>
