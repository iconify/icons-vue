<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zokhwqnxy"/><path class="m3x38wbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:store-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m3x38wbku {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v6H3Zm2 6v12h14V9m-9 12v-6h4v6M9 3v6m6-6v6");
}

.zokhwqnxy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 3h18v6H3Z");
}

</style>
