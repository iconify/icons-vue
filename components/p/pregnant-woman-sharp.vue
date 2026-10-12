<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="uc68r53bv"/><path class="gi-lizbyh"/><path class="pm-4jbbkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pregnant-woman-sharp" /></template>
<style>
.gi-lizbyh {
  d: path("M7.75 21.25V8.75H13v3c2.5.5 4 2.25 4 4.5S15.5 20 13 20.5v.75Z");
}

.pm-4jbbkd {
  d: path("m12.75 14.25l1.5.525v1.475");
}

.uc68r53bv {
  cx: 10.25px;
  cy: 4.5px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
