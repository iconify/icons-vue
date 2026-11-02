<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ya3u2jbaq"/><path class="n_36tibay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-right-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n_36tibay {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 14v2a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V9a3 3 0 0 0-3-3m-4 0H9a4 4 0 0 0-4 4m4-7l3 3l-3 3");
}

.ya3u2jbaq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 10v6a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4v-6a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4");
}

</style>
