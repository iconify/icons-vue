<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wfztb1bqh"/><path class="hbedjw_8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-duocolor-sharp" /></template>
<style>
.hbedjw_8z {
  d: path("M8 16C5.105 13.105 3 9.418 3 5V3h6l2 5l-3 3l2 3m7-1l4 2v6h-2c-2.878 0-5.667-.67-8-2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wfztb1bqh {
  stroke-opacity: 0.4;
  d: path("M2 22L22 2");
}

</style>
