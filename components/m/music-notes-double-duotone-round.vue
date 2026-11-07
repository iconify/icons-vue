<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="afqo38bdn"/><path class="g_8w-rb5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-notes-double-duotone-round" /></template>
<style>
.afqo38bdn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 19a3 3 0 1 1 0-6a3 3 0 0 1 0 6M6 21a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

.ft5dv1b6b {
  fill: none;
}

.g_8w-rb5x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0m12-2a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6 2V9c0-1.437.816-2.662 2-3l7-2c1.503-.43 3 1.067 3 3v9M9 12l12-4");
}

</style>
