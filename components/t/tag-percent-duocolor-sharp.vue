<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xyrbbs_9g"/><path class="dvho1cbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-percent-duocolor-sharp" /></template>
<style>
.dvho1cbbx {
  d: path("M9 3h6l4 4v14H5V7zm2 3h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xyrbbs_9g {
  stroke-opacity: 0.4;
  d: path("m15 11l-6 6m-1-6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
