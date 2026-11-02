<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u7pjc2b7b"/><path class="wvtawvb9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-back-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u7pjc2b7b {
  stroke-opacity: 0.4;
  d: path("M4 5v14");
}

.wvtawvb9t {
  d: path("m16.94 5.304l-8 5a2 2 0 0 0 0 3.392l8 5C18.272 19.529 20 18.571 20 17V7c0-1.57-1.728-2.529-3.06-1.696");
}

</style>
