<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="be7dd7brv"/><path class="oxcpo9bsz"/><path class="e2sd28zws"/><path class="olj_e5cpq"/><path class="mk93lqrnh"/><path class="hzm2gxbyj"/><path class="syh4macvb"/><path class="rsgt5c-rz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:task-split-duotone-thin" /></template>
<style>
.be7dd7brv {
  fill: currentColor;
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h13A2.5 2.5 0 0 1 21 5.5 2.5 2.5 0 0 1 18.5 8h-13A2.5 2.5 0 0 1 3 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e2sd28zws {
  fill: currentColor;
  d: path("M13 16.5a2.5 2.5 0 0 1 2.5 -2.5h3a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-3a2.5 2.5 0 0 1 -2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hzm2gxbyj {
  d: path("M17 8v6");
}

.mk93lqrnh {
  d: path("M7 8v6");
}

.olj_e5cpq {
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h13A2.5 2.5 0 0 1 21 5.5 2.5 2.5 0 0 1 18.5 8h-13A2.5 2.5 0 0 1 3 5.5");
}

.oxcpo9bsz {
  fill: currentColor;
  d: path("M3 16.5A2.5 2.5 0 0 1 5.5 14h3a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 8.5 19h-3A2.5 2.5 0 0 1 3 16.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rsgt5c-rz {
  d: path("M13 16.5a2.5 2.5 0 0 1 2.5 -2.5h3a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-3a2.5 2.5 0 0 1 -2.5 -2.5");
}

.syh4macvb {
  d: path("M3 16.5A2.5 2.5 0 0 1 5.5 14h3a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 8.5 19h-3A2.5 2.5 0 0 1 3 16.5");
}

</style>
