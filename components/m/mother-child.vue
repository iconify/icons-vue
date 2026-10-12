<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="pto36s2zd"/><path class="dzu6fgb_r"/><circle class="jvv3of_em"/><path class="mwbu91bhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mother-child" /></template>
<style>
.dzu6fgb_r {
  d: path("M3.25 21.25L5.1 12.4a2.75 2.75 0 0 1 2.7-2.15h1.4a2.75 2.75 0 0 1 2.7 2.15l1.85 8.85Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvv3of_em {
  cx: 18.75px;
  cy: 11.75px;
  r: 1.75px;
}

.mwbu91bhj {
  d: path("M16.25 21.25V18a2.5 2.5 0 0 1 5 0v3.25Z");
}

.pto36s2zd {
  cx: 8.5px;
  cy: 5.5px;
  r: 2.25px;
}

</style>
