<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e3xlw3esn"/><path class="y6t27cfay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signpost-duocolor-round" /></template>
<style>
.e3xlw3esn {
  stroke-opacity: 0.4;
  d: path("M12 3v3m0 6v9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y6t27cfay {
  d: path("M10 6h5c1.28 0 2.36.36 3 1l1 1a1.414 1.414 0 0 1 0 2l-1 1c-.64.64-1.72 1-3 1H7a3 3 0 0 1 0-6z");
}

</style>
