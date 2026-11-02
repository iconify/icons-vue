<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d3zeogctc"/><path class="k_k89z8xq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rocket-duotone-sharp" /></template>
<style>
.d3zeogctc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 7h2.403c1.038-1.794 2.551-3.103 4.453-3.919C16.784 2.255 18.918 2 21 2a1 1 0 0 1 1 1c-.001 4.233-1.106 8.344-5 10.597V16c0 .637-.158 1.265-.48 1.816C15.617 19.364 13.706 20 12 20a1 1 0 0 1-1-1v-3.586L8.586 13H5a1 1 0 0 1-1-1c0-1.706.636-3.617 2.184-4.52A3.6 3.6 0 0 1 8 7M2 21c0-1.675.068-4.481 1.293-5.707a3.828 3.828 0 0 1 5.414 5.414C7.481 21.932 4.675 22 3 22a1 1 0 0 1-1-1");
}

.ft5dv1b6b {
  fill: none;
}

.k_k89z8xq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 12l2-4c2-4 6-5 10-5c0 4-1 8-5 10l-4 2Zm0 0H5c0-2 1-4 3-4h3m1 7v4c2 0 4-1 4-3v-3M3 21c1 0 4 0 5-1a2.828 2.828 0 1 0-4-4c-1 1-1 4-1 5");
}

</style>
