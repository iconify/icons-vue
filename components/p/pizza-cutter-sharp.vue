<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="fzvmmb14m"/><path class="lwhx5sb4u"/><path class="lfl4uibwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pizza-cutter-sharp" /></template>
<style>
.fzvmmb14m {
  cx: 8.75px;
  cy: 15.25px;
  r: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfl4uibwv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.99 11.01l2.12-2.12m.36.36l-.72-.72l-.88-.88l.88-.88l3.13-3.13l.88-.88l.88.88l.72.72l.88.88l-.88.88l-3.13 3.13l-.88.88z");
}

.lwhx5sb4u {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 15.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
