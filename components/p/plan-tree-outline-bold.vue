<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ffl_tubrp"/><path class="fl42iabgs"/><path class="s4opvo9pz"/><path class="siocq_7mf"/><path class="iic1bs66d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plan-tree-outline-bold" /></template>
<style>
.ffl_tubrp {
  d: path("M7 6.5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2");
}

.fl42iabgs {
  d: path("M12 8.5V12");
}

.iic1bs66d {
  d: path("M14.5 17.75a2.25 2.25 0 0 1 2.25 -2.25h2.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 19.25 20h-2.5a2.25 2.25 0 0 1 -2.25 -2.25");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s4opvo9pz {
  d: path("M6 15.5V12h12v3.5");
}

.siocq_7mf {
  d: path("M2.5 17.75a2.25 2.25 0 0 1 2.25 -2.25h2.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 7.25 20h-2.5a2.25 2.25 0 0 1 -2.25 -2.25");
}

</style>
