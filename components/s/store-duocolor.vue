<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nqqqpab0e"/><path class="hdo8n1buc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:store-duocolor" /></template>
<style>
.hdo8n1buc {
  d: path("M3 5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm2 4v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V9m-9 12v-4a2 2 0 1 1 4 0v4");
}

.nqqqpab0e {
  stroke-opacity: 0.4;
  d: path("M9 3v6m6-6v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
