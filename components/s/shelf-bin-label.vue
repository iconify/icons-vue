<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i04arebvf"/><path class="j20u6abft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shelf-bin-label" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i04arebvf {
  d: path("M4.25 9h12A1.75 1.75 0 0 1 18 10.75v9a1.75 1.75 0 0 1-1.75 1.75h-12a1.75 1.75 0 0 1-1.75-1.75v-9A1.75 1.75 0 0 1 4.25 9M2.5 9L6 3.5h15.5L18 9m3.5-5.5V16L18 21.5");
}

.j20u6abft {
  d: path("M6.5 12.25H14a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5H6.5a1.5 1.5 0 0 1-1.5-1.5v-3a1.5 1.5 0 0 1 1.5-1.5m1 3H13");
}

</style>
