<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jeaqztjrg"/><path class="pxkh6-9_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:neighbour-outline-bold" /></template>
<style>
.jeaqztjrg {
  d: path("M2 18v-6l4 -4 4 4v6Z");
}

.pxkh6-9_k {
  d: path("M14 18v-6l4 -4 4 4v6Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
