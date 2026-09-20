<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w3hyiobto"/><path class="hgb-t7boy"/><path class="ykj59ccld"/><path class="udsnn3bwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:severity-label-outline-bold" /></template>
<style>
.hgb-t7boy {
  d: path("M6 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.udsnn3bwn {
  d: path("M9.5 17.5 12 15l2.5 2.5");
}

.w3hyiobto {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

.ykj59ccld {
  d: path("M9.5 13.5 12 11l2.5 2.5");
}

</style>
