<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="trav75dvw"/><path class="qdnvt9b_j"/><path class="x7vk12b2r"/><path class="waw662eej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quote-compare-duotone-bold" /></template>
<style>
.qdnvt9b_j {
  fill: currentColor;
  d: path("M14 7h7v6l-3.5 3.5L14 13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.trav75dvw {
  fill: currentColor;
  d: path("M3 7h7v6l-3.5 3.5L3 13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.waw662eej {
  d: path("M14 7h7v6l-3.5 3.5L14 13Z");
}

.x7vk12b2r {
  d: path("M3 7h7v6l-3.5 3.5L3 13Z");
}

</style>
