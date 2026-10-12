<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y6hltie2g"/><rect class="dul9o8b0c"/><rect class="ytwxbfbcm"/><path class="d_q_cobxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paste-text" /></template>
<style>
.d_q_cobxs {
  d: path("M14.75 15.25h4m-4 2.75h2.5");
}

.dul9o8b0c {
  width: 7.5px;
  height: 3.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6hltie2g {
  d: path("M18.75 8.75v-2.5a2 2 0 0 0-2-2h-1m-7.5 0h-1a2 2 0 0 0-2 2v12.5a2 2 0 0 0 2 2H9");
}

.ytwxbfbcm {
  width: 9px;
  height: 9.5px;
  x: 12.25px;
  y: 11.75px;
  rx: 1.75px;
}

</style>
