<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d3xn50bni"/><path class="oy7fa3gbk"/><path class="zvb1nubon"/><path class="wuktrpbtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:passport-outline-bold" /></template>
<style>
.d3xn50bni {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.oy7fa3gbk {
  d: path("M8 2v20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wuktrpbtg {
  d: path("M11 15h8");
}

.zvb1nubon {
  d: path("M11 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
