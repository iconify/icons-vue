<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkz22f2th"/><path class="dvho1cbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-plus-duocolor-sharp" /></template>
<style>
.dvho1cbbx {
  d: path("M9 3h6l4 4v14H5V7zm2 3h2");
}

.mkz22f2th {
  stroke-opacity: 0.4;
  d: path("M9 14h6m-3-3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
