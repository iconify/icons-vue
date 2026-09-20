<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xxmghbcrw"/><path class="qlnog1bgn"/><path class="w6fvlpypf"/><path class="vd0jm7r_j"/><path class="zslxt_5nz"/><path class="gvj63pubw"/><path class="ggzo1fbjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stream-job-duotone-bold" /></template>
<style>
.ggzo1fbjx {
  d: path("M6 20h6");
}

.gvj63pubw {
  d: path("M18 16h3");
}

.qlnog1bgn {
  d: path("M6 6a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vd0jm7r_j {
  d: path("M3 16h6");
}

.w6fvlpypf {
  d: path("m9.5 6.5 2 2 -2 2");
}

.xxmghbcrw {
  fill: currentColor;
  d: path("M6 6a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zslxt_5nz {
  d: path("M12 16h3");
}

</style>
