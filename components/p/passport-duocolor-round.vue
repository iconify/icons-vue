<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oncbk1b8w"/><path class="fcr8reb_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passport-duocolor-round" /></template>
<style>
.fcr8reb_t {
  d: path("M5 7a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4Zm4 10h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oncbk1b8w {
  stroke-opacity: 0.4;
  d: path("M9 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
