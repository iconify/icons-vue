<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sb2v8ybxo"/><path class="qvg1frb6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qvg1frb6n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 10a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v7a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4Zm4-4a3 3 0 0 1 6 0");
}

.sb2v8ybxo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 5h6a5 5 0 0 1 5 5v7a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5v-7a5 5 0 0 1 5-5");
}

</style>
