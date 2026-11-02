<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oncbk1b8w"/><path class="f101g7mzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passport-duocolor-sharp" /></template>
<style>
.f101g7mzi {
  d: path("M5 3h14v18H5Zm4 14h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oncbk1b8w {
  stroke-opacity: 0.4;
  d: path("M9 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
