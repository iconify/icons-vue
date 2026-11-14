<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rbselc28d"/><path class="x5lxgdb9t"/><path class="saktft54v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tyre-trolley" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rbselc28d {
  d: path("M6.25 9.5a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0");
}

.saktft54v {
  d: path("M3.5 17.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m13 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7-7.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.x5lxgdb9t {
  d: path("M2.5 9v6.25h19");
}

</style>
