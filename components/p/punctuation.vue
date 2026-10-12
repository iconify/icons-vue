<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5vaj9bqz"/><circle class="l78ls8mni"/><circle class="frsmk1b8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:punctuation" /></template>
<style>
.frsmk1b8c {
  cx: 17px;
  cy: 19px;
  r: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l78ls8mni {
  cx: 7.5px;
  cy: 19px;
  r: 1.25px;
}

.x5vaj9bqz {
  d: path("M3.75 7.5a3.75 3.75 0 1 1 5.8 3.15c-1.2.8-2.05 1.7-2.05 3.1v1m9.5-11v11");
}

</style>
