<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wn8i1hruc"/><path class="q38rixd8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q38rixd8d {
  d: path("M3 3h14l4 4v14H3zm4 18v-7h10v7");
}

.wn8i1hruc {
  stroke-opacity: 0.4;
  d: path("M9 7h6");
}

</style>
