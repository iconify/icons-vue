<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="amztffb2r"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="byv-jbcgv"/><path class="jhw2btbwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:school-bus-clock-sharp" /></template>
<style>
.amztffb2r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h13.5v5.5h4v6.5H2.75v-12zm-1 4.75h14.5M7.5 4.75V9.5m4.75-4.75V9.5");
}

.byv-jbcgv {
  cx: 17.25px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhw2btbwa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 19h.01");
}

.ox2ue_b-w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

.r_0b548wt {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
