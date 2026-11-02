<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zo-v9hbio"/><path class="tm4skiqux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-off-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tm4skiqux {
  d: path("M6 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6 0v-3m0-6V4l6 3");
}

.zo-v9hbio {
  stroke-opacity: 0.4;
  d: path("m2 4l18 18");
}

</style>
