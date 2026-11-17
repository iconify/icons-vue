<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j04wud_og"/><path class="hjk1rtx3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hjk1rtx3u {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16L15 5a1.414 1.414 0 0 1 2 0l2 2a1.414 1.414 0 0 1 0 2L8 20m0 0H4v-4m7-11L9 7m10 6l-2 2m-4-8l-3-3a1.414 1.414 0 0 0-2 0L4 8a1.414 1.414 0 0 0 0 2l3 3m10-2l3 3a1.414 1.414 0 0 1 0 2l-4 4a1.414 1.414 0 0 1-2 0l-3-3");
}

.j04wud_og {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 20v-4L15 5a1.415 1.415 0 0 1 2 0l2 2a1.415 1.415 0 0 1 0 2L8 20Z");
}

</style>
