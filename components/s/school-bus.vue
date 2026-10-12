<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="l4wcekurn"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="byv-jbcgv"/><path class="jhw2btbwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:school-bus" /></template>
<style>
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

.l4wcekurn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h12.5a1 1 0 0 1 1 1v4.5h2a2 2 0 0 1 2 2v3.5a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1v-10a1 1 0 0 1 1-1m-1 4.75h14.5M7.5 4.75V9.5m4.75-4.75V9.5");
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

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
