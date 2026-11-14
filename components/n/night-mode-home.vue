<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r8_6hk26m"/><path class="wdzg1ve9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:night-mode-home" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r8_6hk26m {
  d: path("m5.195 9.454l4.5-3.937a3.5 3.5 0 0 1 4.61 0l5.036 4.407A1.93 1.93 0 0 1 20 11.375a.875.875 0 0 1-.875.875H15.75a3.5 3.5 0 0 0-3.5 3.5v.75a3.5 3.5 0 0 1-3.5 3.5H7.5A3.5 3.5 0 0 1 4 16.5v-4.412a3.5 3.5 0 0 1 1.195-2.634");
}

.wdzg1ve9z {
  d: path("M21 19.25A3.5 3.5 0 1 1 16.75 15A2.75 2.75 0 0 0 21 19.25");
}

</style>
