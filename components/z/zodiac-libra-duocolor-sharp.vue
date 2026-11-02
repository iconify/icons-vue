<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pde-hjbub"/><path class="iukp7hf7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-libra-duocolor-sharp" /></template>
<style>
.iukp7hf7b {
  d: path("M4 17h5v-1a6.708 6.708 0 1 1 6 0v1h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pde-hjbub {
  stroke-opacity: 0.4;
  d: path("M4 21h16");
}

</style>
