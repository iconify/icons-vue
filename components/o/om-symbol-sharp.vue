<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="u5iak3btt"/><path class="zr8jwub-x"/><path class="zo02lrkix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:om-symbol-sharp" /></template>
<style>
.u5iak3btt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.25 6l1.324-1.25H7.5a3 3 0 0 1 0 6H6.25m1.25 0a4.5 4.5 0 1 1-3.75 7");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zo02lrkix {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 3.25h.01");
}

.zr8jwub-x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 14.25c1-1.75 2.25-2.75 3.75-2.75c2.25 0 3.75 2 3.75 4.75S17.75 21 15.75 21m-2-14.75l2.5 3l2.5-3");
}

</style>
