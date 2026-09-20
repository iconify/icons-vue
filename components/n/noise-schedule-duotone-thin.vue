<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zc7-aybrt"/><path class="a4ntl3b-i"/><path class="oiuqz28dl"/><path class="tly31jb6g"/><path class="o5r_prbgx"/><path class="xrw775b-m"/><path class="el8_zutrb"/><path class="wc07w8blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:noise-schedule-duotone-thin" /></template>
<style>
.a4ntl3b-i {
  fill: currentColor;
  d: path("M10 9.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.el8_zutrb {
  d: path("M16 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5r_prbgx {
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.oiuqz28dl {
  fill: currentColor;
  d: path("M16 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tly31jb6g {
  fill: currentColor;
  d: path("M20 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wc07w8blj {
  d: path("M20 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xrw775b-m {
  d: path("M10 9.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zc7-aybrt {
  fill: currentColor;
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
