<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lyrljtv-p"/><path class="vr4jlwbtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:owl-duocolor" /></template>
<style>
.lyrljtv-p {
  stroke-opacity: 0.4;
  d: path("M6 10a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m8 0a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m-2 3v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vr4jlwbtq {
  d: path("M4 3c2.5 1.5 5 2 8 2s5.5-.5 8-2c1 2.5 1 4.5 1 7c0 4.5-4 8-9 8s-9-3.5-9-8c0-2.5 0-4.5 1-7M3 21h18m-11-3v3m4-3v3");
}

</style>
