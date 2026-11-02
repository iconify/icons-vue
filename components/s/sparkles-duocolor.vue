<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iphozxige"/><path class="a68azobdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sparkles-duocolor" /></template>
<style>
.a68azobdc {
  d: path("M9 9c0 3 3 6 6 6c-3 0-6 3-6 6c0-3-3-6-6-6c3 0 6-3 6-6");
}

.iphozxige {
  stroke-opacity: 0.4;
  d: path("M17 3c0 3.75.25 4 4 4c-3.75 0-4 .25-4 4c0-3.75-.25-4-4-4c3.75 0 4-.25 4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
