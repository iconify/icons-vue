<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dwltyfb3p"/><path class="xwbv0l_7u"/><path class="sqk_bfbxp"/><path class="ncr6vm62v"/><path class="l5r0hwbum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prompt-stuffing-outline-thin" /></template>
<style>
.dwltyfb3p {
  d: path("M2 8a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5r0hwbum {
  d: path("m18 10 3 3 -3 3");
}

.ncr6vm62v {
  d: path("M4 16h8");
}

.sqk_bfbxp {
  d: path("M4 13h8");
}

.xwbv0l_7u {
  d: path("M4 10h8");
}

</style>
