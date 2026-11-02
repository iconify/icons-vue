<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="isqhwqbmr"/><path class="oiladab4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-side-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.isqhwqbmr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 4c.351 0 .677.184.857.486L8.566 9H21a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-5.586l-4.707 4.707A1 1 0 0 1 10 20H8a1 1 0 0 1-.928-1.371L8.523 15H5a1 1 0 0 1-.976-.783l-2-9A1 1 0 0 1 3 4Z");
}

.oiladab4b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5h2l3 5h13v4h-6l-5 5H8l2-5H5z");
}

</style>
