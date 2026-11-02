<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="upiwdxonc"/><path class="lw6t35brr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-duocolor-sharp" /></template>
<style>
.lw6t35brr {
  d: path("M4 4h16v16H4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.upiwdxonc {
  stroke-opacity: 0.4;
  d: path("M15 4v16");
}

</style>
