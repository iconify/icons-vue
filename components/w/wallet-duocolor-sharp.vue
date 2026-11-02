<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jbutoqb1r"/><path class="w7mc2oblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallet-duocolor-sharp" /></template>
<style>
.jbutoqb1r {
  stroke-opacity: 0.4;
  d: path("M21 9h-6v6h6m-3-3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w7mc2oblu {
  d: path("M3 4h18v16H3Z");
}

</style>
