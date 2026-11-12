<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ur7h5bb6e"/><path class="ba5kewmmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:segmented-control-duocolor-sharp" /></template>
<style>
.ba5kewmmn {
  d: path("M3 6h18v12H3Zm14 6h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ur7h5bb6e {
  stroke-opacity: 0.4;
  d: path("M6 9h6v6H6Z");
}

</style>
