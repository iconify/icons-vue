<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e0q0hkb6i"/><path class="vc5d-hb4f"/><rect class="j7wt_6bod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:step-well" /></template>
<style>
.e0q0hkb6i {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7wt_6bod {
  width: 2.5px;
  height: 2.5px;
  x: 10.75px;
  y: 10.75px;
  rx: 0.5px;
}

.vc5d-hb4f {
  d: path("M5.75 6.75a1 1 0 0 1 1-1h10.5a1 1 0 0 1 1 1v10.5a1 1 0 0 1-1 1H6.75a1 1 0 0 1-1-1ZM8.25 9A.75.75 0 0 1 9 8.25h6a.75.75 0 0 1 .75.75v6a.75.75 0 0 1-.75.75H9a.75.75 0 0 1-.75-.75Z");
}

</style>
