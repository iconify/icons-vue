<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yymvhuctj"/><circle class="xe95m5bil"/><circle class="uit8fi3go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:music-download" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uit8fi3go {
  cx: 17.75px;
  cy: 15.25px;
  r: 2.75px;
}

.xe95m5bil {
  cx: 6.25px;
  cy: 17.25px;
  r: 2.75px;
}

.yymvhuctj {
  d: path("M9 17.25V6.35a1 1 0 0 1 .8-.98l9.5-1.9a1 1 0 0 1 1.2.98v10.8");
}

</style>
