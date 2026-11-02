<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p6iuugbcz"/><path class="sksp51b7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rocket-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p6iuugbcz {
  stroke-opacity: 0.4;
  d: path("M3 21c1 0 4 0 5-1a2.828 2.828 0 1 0-4-4c-1 1-1 4-1 5");
}

.sksp51b7n {
  d: path("m9 12l2-4c2-4 6-5 10-5c0 4-1 8-5 10l-4 2Zm0 0H5c0-2 1-4 3-4h3m1 7v4c2 0 4-1 4-3v-3");
}

</style>
