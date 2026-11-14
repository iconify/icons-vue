<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="whvb58bhv"/><path class="j1qb57b4m"/><path class="hbkond58l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:refresh-circle" /></template>
<style>
.hbkond58l {
  d: path("m5.5 14l2-2l2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1qb57b4m {
  d: path("m14.5 10l2 2l2-2m-2.603 4.25A4.5 4.5 0 0 1 7.5 12");
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.whvb58bhv {
  d: path("M8.103 9.75A4.5 4.5 0 0 1 16.5 12");
}

</style>
