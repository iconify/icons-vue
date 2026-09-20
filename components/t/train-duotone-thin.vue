<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="in6t1tblh"/><path class="w33xiq-if"/><path class="jof7c9fpk"/><path class="e4mo_8b_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:train-duotone-thin" /></template>
<style>
.e4mo_8b_s {
  d: path("M3 22h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.in6t1tblh {
  fill: currentColor;
  d: path("M4 19V9a5 5 0 0 1 16 0v10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jof7c9fpk {
  d: path("M4 9h16");
}

.w33xiq-if {
  d: path("M4 19V9a5 5 0 0 1 16 0v10Z");
}

</style>
