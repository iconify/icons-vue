<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h_ahrlbwq"/><path class="c6ge0ib5p"/><path class="ywd80sbef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ticker-outline-bold" /></template>
<style>
.c6ge0ib5p {
  d: path("M15 12a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.h_ahrlbwq {
  d: path("M2 10a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ywd80sbef {
  d: path("M5 13.5 7.5 11l2.5 2.5 2.5 -2.5");
}

</style>
