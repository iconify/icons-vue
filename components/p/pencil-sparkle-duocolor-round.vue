<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ktosslrvs"/><path class="znaljbwrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-sparkle-duocolor-round" /></template>
<style>
.ktosslrvs {
  stroke-opacity: 0.4;
  d: path("M6 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3m12 12c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.znaljbwrv {
  d: path("M5 19v-3l9-9a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 1 0 2l-9 9zm8-11l3 3");
}

</style>
