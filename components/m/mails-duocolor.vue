<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n8lrkx_yj"/><path class="e6bi77b-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mails-duocolor" /></template>
<style>
.e6bi77b-p {
  d: path("M3 11a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm1-1l4 4c.64.64 1.36 1 2 1s1.36-.36 2-1l4-4");
}

.n8lrkx_yj {
  stroke-opacity: 0.4;
  d: path("M7 5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
