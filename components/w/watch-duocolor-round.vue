<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mwg9_qb3b"/><path class="k6mfu6bqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:watch-duocolor-round" /></template>
<style>
.k6mfu6bqi {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 0 0-10 0m2-4V6a3 3 0 0 1 6 0v2m-6 8v2a3 3 0 0 0 6 0v-2");
}

.mwg9_qb3b {
  stroke-opacity: 0.4;
  d: path("M12 10v2h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
