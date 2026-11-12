<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="dtl23o_xq"/><path class="l0wsz0bge"/><path class="u7-f98bkg"/><ellipse class="jr044sswv"/><path class="t5koibbkf"/><path class="qqdkw_blr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:users-group-two-rounded-line-duotone" /></template>
<style>
.dtl23o_xq {
  cx: 12px;
  cy: 6px;
  r: 4px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jr044sswv {
  cx: 12px;
  cy: 17px;
  rx: 6px;
  ry: 4px;
}

.l0wsz0bge {
  d: path("M18 9C19.6569 9 21 7.88071 21 6.5C21 5.11929 19.6569 4 18 4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qqdkw_blr {
  d: path("M4 19C2.24575 18.6153 1 17.6411 1 16.5C1 15.3589 2.24575 14.3847 4 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.t5koibbkf {
  d: path("M20 19C21.7542 18.6153 23 17.6411 23 16.5C23 15.3589 21.7542 14.3847 20 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.u7-f98bkg {
  d: path("M6 9C4.34315 9 3 7.88071 3 6.5C3 5.11929 4.34315 4 6 4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
