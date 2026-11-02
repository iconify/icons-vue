<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axcf-wb4p"/><path class="w9uwdypwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-duocolor-round" /></template>
<style>
.axcf-wb4p {
  stroke-opacity: 0.4;
  d: path("m2 2l20 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w9uwdypwq {
  d: path("M8 8a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h1c.64 0 1.36.36 2 1l1 1c.738.738 2 .107 2-1v-3m0-6V7c0-1.107-1.262-1.738-2-1");
}

</style>
