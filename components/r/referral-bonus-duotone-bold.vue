<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f-t_rcb_j"/><path class="wajv_y-6p"/><path class="u856qebtg"/><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="oewjtrp_y"/><path class="z8jb6te8i"/><path class="ijxaf0bnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:referral-bonus-duotone-bold" /></template>
<style>
.f-t_rcb_j {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ijxaf0bnr {
  d: path("M7 17.5h10");
}

.k6fi9qmtq {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.oewjtrp_y {
  d: path("M7 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u856qebtg {
  fill: currentColor;
  d: path("M13 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wajv_y-6p {
  fill: currentColor;
  d: path("M7 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z8jb6te8i {
  d: path("M13 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
