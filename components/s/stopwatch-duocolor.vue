<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dio1l6b5t"/><path class="ubqfwcbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stopwatch-duocolor" /></template>
<style>
.dio1l6b5t {
  stroke-opacity: 0.4;
  d: path("M12 13V9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ubqfwcbya {
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 0 0-16 0m6-10h4m-2 0v2m6 2l2-2");
}

</style>
