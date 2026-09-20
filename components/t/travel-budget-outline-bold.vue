<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d3xn50bni"/><path class="j9d013d3m"/><path class="h4gaqv9on"/><path class="jz10k5bkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-budget-outline-bold" /></template>
<style>
.d3xn50bni {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.h4gaqv9on {
  d: path("M11.5 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.j9d013d3m {
  d: path("M9 2v20");
}

.jz10k5bkg {
  d: path("M14.5 10v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
