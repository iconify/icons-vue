<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n_-2-nbyf"/><path class="xfkqvbc7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stethoscope-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n_-2-nbyf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 10a2 2 0 1 1 3.999-.001A2 2 0 0 1 17 10");
}

.xfkqvbc7v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 4a2 2 0 0 0-2 2v5a4 4 0 1 0 8 0V6a2 2 0 0 0-2-2M5 3v2m4-2v2M7 15a6 6 0 1 0 12 0v-3m-2-2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
