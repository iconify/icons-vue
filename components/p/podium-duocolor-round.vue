<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tp-oq1upk"/><path class="bq8rv2bki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:podium-duocolor-round" /></template>
<style>
.bq8rv2bki {
  d: path("M8 12H5a2 2 0 0 0-2 2v3a4 4 0 0 0 4 4h1m8-6h3a2 2 0 0 1 2 2v1a3 3 0 0 1-3 3h-2m-8 0V7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v14z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tp-oq1upk {
  stroke-opacity: 0.4;
  d: path("m11 11l2-2v6");
}

</style>
