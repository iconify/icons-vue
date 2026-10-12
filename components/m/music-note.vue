<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mv21fmbrx"/><circle class="zzmj1gk8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:music-note" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mv21fmbrx {
  d: path("M11.5 17V3.75c0 1.9 1.7 3.1 3.5 3.6c1.4.4 2.75 1.4 2.75 3.15");
}

.zzmj1gk8v {
  cx: 8.25px;
  cy: 17px;
  r: 3.25px;
}

</style>
