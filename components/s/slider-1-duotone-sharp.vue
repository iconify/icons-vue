<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n-hehbbag"/><path class="shaksbcfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-1-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n-hehbbag {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 11a2 2 0 1 1-.001-3.999A2 2 0 0 1 16 11m-8 6a2 2 0 1 1-.001-3.999A2 2 0 0 1 8 17");
}

.shaksbcfy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-8 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0M3 9h11m4 0h3M3 15h3m4 0h11");
}

</style>
