<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gax8di68h"/><rect class="z206m0bqn"/><path class="wk22e6-7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rotation-lock" /></template>
<style>
.gax8di68h {
  d: path("M16.25 4.64a8.5 8.5 0 1 1-8.5 0M4.93 3.61l2.82 1.03l-.52 2.95");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wk22e6-7t {
  d: path("M10.25 11.25V10a1.75 1.75 0 0 1 3.5 0v1.25");
}

.z206m0bqn {
  width: 6px;
  height: 5px;
  x: 9px;
  y: 11.25px;
  rx: 1px;
}

</style>
