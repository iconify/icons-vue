<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jm-bl79zb"/><path class="m2cth_6av"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stepper-duocolor-sharp" /></template>
<style>
.jm-bl79zb {
  stroke-opacity: 0.4;
  d: path("M3 18h6m6 0h6m-3-3v6");
}

.m2cth_6av {
  d: path("M3 3h18v8H3Zm4 4h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
