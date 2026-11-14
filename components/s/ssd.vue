<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3_eu9b1r"/><path class="ng8fw3bzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ssd" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ng8fw3bzh {
  d: path("M10.75 9.5h2.5A1.75 1.75 0 0 1 15 11.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 12.75v-1.5a1.75 1.75 0 0 1 1.75-1.75m-8.25-1h3m-3 3.5h3m-3 3.5h3m13-7h3m-3 3.5h3m-3 3.5h3");
}

.r3_eu9b1r {
  d: path("M9 5h6a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 15 19H9a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 9 5");
}

</style>
