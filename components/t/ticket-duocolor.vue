<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b5_asfvzt"/><path class="sgxn6-bdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ticket-duocolor" /></template>
<style>
.b5_asfvzt {
  stroke-opacity: 0.4;
  d: path("M14 6v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sgxn6-bdn {
  d: path("M21 9V8a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v1a3 3 0 0 1 0 6v1a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-1a3 3 0 0 1 0-6");
}

</style>
