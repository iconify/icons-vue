<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="sd6wdsdpf"/><path class="xe5njdbqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:retort" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sd6wdsdpf {
  cx: 8.75px;
  cy: 14.5px;
  r: 6px;
}

.xe5njdbqo {
  d: path("M2.95 16h11.6M13 10.25c1.5-4.75 3.75-6.5 5.25-4.5l3 7.25");
}

</style>
