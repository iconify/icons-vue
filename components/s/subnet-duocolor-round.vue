<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e3q570jrh"/><path class="ypodpcbkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subnet-duocolor-round" /></template>
<style>
.e3q570jrh {
  stroke-opacity: 0.4;
  d: path("M7 16h.01M12 16h.01M17 16h.01M12 7v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ypodpcbkm {
  d: path("M3 15a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm7-10a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
