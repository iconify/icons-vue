<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e7wxh0bvw"/><path class="byhidvb7y"/><circle class="rm7-u063v"/><path class="s2zveysro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tenant-person" /></template>
<style>
.byhidvb7y {
  d: path("M2.75 21.25V20a4.5 4.5 0 0 1 4.5-4.5h3.5a4.5 4.5 0 0 1 4.5 4.5v1.25Z");
}

.e7wxh0bvw {
  cx: 9px;
  cy: 7.25px;
  r: 3.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rm7-u063v {
  cx: 18.25px;
  cy: 6.5px;
  r: 2.75px;
}

.s2zveysro {
  d: path("M18.25 9.25v8m0-3.75h2.25M18.25 16H20");
}

</style>
