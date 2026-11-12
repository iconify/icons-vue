<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e3q570jrh"/><path class="bt7wo-bji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subnet-duocolor" /></template>
<style>
.bt7wo-bji {
  d: path("M3 13a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm7-8a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

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

</style>
