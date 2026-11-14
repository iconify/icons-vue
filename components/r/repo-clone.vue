<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u508km-1d"/><path class="cnsb5n80n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repo-clone" /></template>
<style>
.cnsb5n80n {
  d: path("M3 17V4.5a2 2 0 0 1 2-2h12m-6.25 4v15M14 6.5v5l1.75-1.25l1.75 1.25v-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u508km-1d {
  d: path("M11 6.5h6.5A3.5 3.5 0 0 1 21 10v8a3.5 3.5 0 0 1-3.5 3.5H11A3.5 3.5 0 0 1 7.5 18v-8A3.5 3.5 0 0 1 11 6.5");
}

</style>
