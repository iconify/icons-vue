<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jku9-obej"/><path class="jodp59bzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-voice-duocolor-sharp" /></template>
<style>
.jku9-obej {
  stroke-opacity: 0.4;
  d: path("M17 4a6.7 6.7 0 0 1 0 6m3-7a9.85 9.85 0 0 1 0 8");
}

.jodp59bzf {
  d: path("M5 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21a6 6 0 1 1 12 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
