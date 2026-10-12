<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="qi_z9gbzx"/><circle class="pf0l2ptyv"/><circle class="c4yce5bdg"/><path class="pf68-yb5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reasoning-steps" /></template>
<style>
.c4yce5bdg {
  cx: 5.25px;
  cy: 19px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pf0l2ptyv {
  cx: 5.25px;
  cy: 12px;
  r: 1.75px;
}

.pf68-yb5h {
  d: path("M5.25 7.5v2m0 5v2M10 5h11.25M10 12h9m-9 7h6");
}

.qi_z9gbzx {
  cx: 5.25px;
  cy: 5px;
  r: 1.75px;
}

</style>
