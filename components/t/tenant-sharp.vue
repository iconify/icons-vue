<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e7wxh0bvw"/><path class="crg1i76ng"/><circle class="rm7-u063v"/><path class="s2zveysro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tenant-sharp" /></template>
<style>
.crg1i76ng {
  d: path("M2.75 21.25V15.5h12.5v5.75Z");
}

.e7wxh0bvw {
  cx: 9px;
  cy: 7.25px;
  r: 3.75px;
}

.rm7-u063v {
  cx: 18.25px;
  cy: 6.5px;
  r: 2.75px;
}

.s2zveysro {
  d: path("M18.25 9.25v8m0-3.75h2.25M18.25 16H20");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
