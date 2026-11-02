<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nhn27swpu"/><path class="o5g87024y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:robot-duocolor-sharp" /></template>
<style>
.nhn27swpu {
  stroke-opacity: 0.4;
  d: path("M9 13v2m6-2v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o5g87024y {
  d: path("M5 9h14v12H5Zm7 0V5m-1-1a1 1 0 1 0 2 0a1 1 0 0 0-2 0M5 15H3m16 0h2");
}

</style>
