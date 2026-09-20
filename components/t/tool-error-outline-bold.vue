<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tlah7acnn"/><path class="elo_ccj2r"/><path class="yz_nd208h"/><path class="r68i47b4w"/><path class="c6_1lkb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tool-error-outline-bold" /></template>
<style>
.c6_1lkb2d {
  d: path("m14 13.5 -4 4");
}

.elo_ccj2r {
  d: path("M9 4v7");
}

.r68i47b4w {
  d: path("m10 13.5 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tlah7acnn {
  d: path("M6 13a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.yz_nd208h {
  d: path("M15 4v7");
}

</style>
