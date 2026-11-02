<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pqczucbfa"/><path class="rew68cb8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stethoscope-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqczucbfa {
  stroke-opacity: 0.4;
  d: path("M7 15a6 6 0 1 0 12 0v-3m-2-2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.rew68cb8n {
  d: path("M5 4H3v7a4 4 0 1 0 8 0V4H9M5 3v2m4-2v2");
}

</style>
