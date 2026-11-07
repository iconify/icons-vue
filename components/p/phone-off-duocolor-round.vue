<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wfztb1bqh"/><path class="vcfhiab1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vcfhiab1w {
  d: path("M7.686 16.314A15.95 15.95 0 0 1 3 5a2 2 0 0 1 2-2h1c1.691 0 3.275 1.188 4 3c.693 1.733.693 3.307 0 4a2.12 2.12 0 0 0 0 3l.5.5M15 15c.64-.64 1.72-1 3-1h1c1.105 0 2 1.79 2 4v1a2 2 0 0 1-2 2c-2.878 0-5.578-.76-7.91-2.09");
}

.wfztb1bqh {
  stroke-opacity: 0.4;
  d: path("M2 22L22 2");
}

</style>
