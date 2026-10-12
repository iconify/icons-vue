<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="aermkxboq"/><path class="gk9brvfbv"/><path class="qnyo8yb5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tag-people-sharp" /></template>
<style>
.aermkxboq {
  cx: 8.5px;
  cy: 6.5px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gk9brvfbv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 19.75h-1v-1a5.75 5.75 0 0 1 11.5 0v1h-1ZM15.5 3.5h3.25l.61.79l1.28 1.67l.61.79l-.61.79l-1.28 1.67l-.61.79H14.5V3.5z");
}

.qnyo8yb5b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 6.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
