<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dqtszy6sm"/><path class="nybt6xb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scissors-duocolor" /></template>
<style>
.dqtszy6sm {
  stroke-opacity: 0.4;
  d: path("M3 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0m0 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nybt6xb3m {
  d: path("M8.121 15.879L21 3M8.121 8.121L12 12m3 3l6 6");
}

</style>
