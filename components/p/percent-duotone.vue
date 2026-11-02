<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u5hp29b1q"/><path class="a478hvbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:percent-duotone" /></template>
<style>
.a478hvbql {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 5L5 19M5 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ft5dv1b6b {
  fill: none;
}

.u5hp29b1q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 9a2 2 0 1 1-.001-3.999A2 2 0 0 1 7 9m10 10a2 2 0 1 1-.001-3.999A2 2 0 0 1 17 19");
}

</style>
