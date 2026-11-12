<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="dtl23o_xq"/><path class="t8nx60bkw"/><path class="c7w-2cb_a"/><ellipse class="jr044sswv"/><path class="jds3y3oir"/><path class="k34s5gtmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:users-group-two-rounded-linear" /></template>
<style>
.c7w-2cb_a {
  d: path("M6 9C4.34315 9 3 7.88071 3 6.5C3 5.11929 4.34315 4 6 4");
}

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

.jds3y3oir {
  d: path("M20 19C21.7542 18.6153 23 17.6411 23 16.5C23 15.3589 21.7542 14.3847 20 14");
}

.jr044sswv {
  cx: 12px;
  cy: 17px;
  rx: 6px;
  ry: 4px;
}

.k34s5gtmh {
  d: path("M4 19C2.24575 18.6153 1 17.6411 1 16.5C1 15.3589 2.24575 14.3847 4 14");
}

.t8nx60bkw {
  d: path("M18 9C19.6569 9 21 7.88071 21 6.5C21 5.11929 19.6569 4 18 4");
}

</style>
