<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wre2-1qaq"/><path class="ycb-w6pqj"/><path class="n88inkb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stub-tool-outline-bold" /></template>
<style>
.n88inkb8l {
  d: path("M15 5v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wre2-1qaq {
  d: path("M6 13a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.ycb-w6pqj {
  d: path("M9 5v3");
}

</style>
