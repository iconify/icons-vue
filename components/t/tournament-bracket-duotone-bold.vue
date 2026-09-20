<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rxwr8htky"/><path class="foytbhsts"/><path class="sj6dfcbdj"/><path class="yp_l0abrr"/><path class="rdhgnbc4d"/><path class="qno8l4b9z"/><path class="nuz6-76is"/><path class="l3ca9u8kt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tournament-bracket-duotone-bold" /></template>
<style>
.foytbhsts {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h6v7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l3ca9u8kt {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nuz6-76is {
  d: path("M15 12h6");
}

.qno8l4b9z {
  d: path("M3 19h6v-7");
}

.rdhgnbc4d {
  d: path("M3 5h6v7h6");
}

.rxwr8htky {
  fill: currentColor;
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sj6dfcbdj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h6v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yp_l0abrr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
