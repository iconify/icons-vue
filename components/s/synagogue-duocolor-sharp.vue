<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wbmm5u2vb"/><path class="uc7i5acyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uc7i5acyb {
  d: path("M4 21V8l8-4l8 4v13z");
}

.wbmm5u2vb {
  stroke-opacity: 0.4;
  d: path("m12 9l3.464 6H8.536Zm0 8l3.464-6H8.536Z");
}

</style>
