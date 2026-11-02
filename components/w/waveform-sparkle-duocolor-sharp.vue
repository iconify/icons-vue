<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0gwuybdo"/><path class="v6exm6bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:waveform-sparkle-duocolor-sharp" /></template>
<style>
.n0gwuybdo {
  stroke-opacity: 0.4;
  d: path("M18 9c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v6exm6bcq {
  d: path("M3 10v4m4-8v12m4-9v6");
}

</style>
