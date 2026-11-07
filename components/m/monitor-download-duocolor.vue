<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l2mfjsrty"/><path class="oqu4abb4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-download-duocolor" /></template>
<style>
.l2mfjsrty {
  stroke-opacity: 0.4;
  d: path("m9 11l3 3l3-3m-3 3V7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqu4abb4q {
  d: path("M4 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm5 14h6");
}

</style>
