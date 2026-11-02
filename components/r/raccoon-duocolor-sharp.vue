<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sx51nsb1t"/><path class="p0m1qu7vu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:raccoon-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p0m1qu7vu {
  d: path("M12 6c1.5 0 2.5-.2 3-1c.8-1.4 1.8-2 3-2c1.5 0 2 1 2 3c0 1.5 1 2.5 1 4v7h-2c-1 2.5-3.5 4-7 4s-6-1.5-7-4H3v-7c0-1.5 1-2.5 1-4c0-2 .5-3 2-3c1.2 0 2.2.6 3 2c.5.8 1.5 1 3 1m-3 6h.01M15 12h.01M12 18h.01");
}

.sx51nsb1t {
  stroke-opacity: 0.4;
  d: path("M12 10c1-.7 2-1 3-1q3 0 3 3c0 1.7-.8 3-2 3h-1c-1.4 0-2.4-.8-3-2m0-3c-1-.7-2-1-3-1q-3 0-3 3c0 1.7.8 3 2 3h1c1.4 0 2.4-.8 3-2");
}

</style>
