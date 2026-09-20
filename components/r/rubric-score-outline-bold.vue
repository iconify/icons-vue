<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dx3ubrb9h"/><path class="hbtmd5b0k"/><path class="qxdj2fbrx"/><path class="pdux64boo"/><path class="eqk2m_q5d"/><path class="cyrclk6ai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rubric-score-outline-bold" /></template>
<style>
.cyrclk6ai {
  d: path("M14.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dx3ubrb9h {
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.eqk2m_q5d {
  d: path("M9 15h4");
}

.hbtmd5b0k {
  d: path("M9.5 7V2.5h5V7");
}

.pdux64boo {
  d: path("M14.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qxdj2fbrx {
  d: path("M9 11h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
