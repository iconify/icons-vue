<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="unu7n2b0o"/><path class="n2wmvdxwf"/><path class="gmiwawr0s"/><path class="pywr_yykw"/><path class="m0hvambgh"/><path class="gr_e4eenb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:seasonal-sale-duotone-bold" /></template>
<style>
.gmiwawr0s {
  fill: currentColor;
  d: path("M9 15a4.5 4.5 0 0 1 6 -6 4.5 4.5 0 0 1 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gr_e4eenb {
  d: path("M9 15a4.5 4.5 0 0 1 6 -6 4.5 4.5 0 0 1 -6 6");
}

.m0hvambgh {
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n2wmvdxwf {
  fill: currentColor;
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pywr_yykw {
  d: path("m4 12 8 -8h8v8l-8 8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.unu7n2b0o {
  fill: currentColor;
  d: path("m4 12 8 -8h8v8l-8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
