<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r5a5a_pkh"/><path class="vi4dticeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-left-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r5a5a_pkh {
  stroke-opacity: 0.4;
  d: path("M3 5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.vi4dticeo {
  d: path("M18 3h1a2 2 0 0 1 2 2v1m0 12v1a2 2 0 0 1-2 2h-1M6 21H5a2 2 0 0 1-2-2v-1m18-8v4m-7 7h-4");
}

</style>
