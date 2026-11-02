<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="addxdebsa"/><path class="acvksh7ft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stopwatch-duotone-round" /></template>
<style>
.acvksh7ft {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 0 0-16 0m6-10h4m-2 0v2m6 2l2-2m-8 8V9");
}

.addxdebsa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 13a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

.ft5dv1b6b {
  fill: none;
}

</style>
