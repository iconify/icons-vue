<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g9vxpxqky"/><path class="fdzmn7ijz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-duocolor-round" /></template>
<style>
.fdzmn7ijz {
  d: path("m11 8l6-3c1.838-.919 4 .162 4 2v8c0 1.838-2.162 2.919-4 2l-6-3zm0 0H6a3 3 0 0 0 0 6h5");
}

.g9vxpxqky {
  stroke-opacity: 0.4;
  d: path("M5 14v5a2 2 0 1 0 4 0v-5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
