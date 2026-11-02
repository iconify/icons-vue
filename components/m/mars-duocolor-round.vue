<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r805trlnc"/><path class="vde49ebwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mars-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r805trlnc {
  stroke-opacity: 0.4;
  d: path("m12 12l9-9m-6 0h6v6");
}

.vde49ebwh {
  d: path("M3 16a5 5 0 1 0 10 0a5 5 0 0 0-10 0");
}

</style>
