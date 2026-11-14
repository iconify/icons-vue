<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ghdle1bhl"/><path class="b_pzjjb1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:query-result" /></template>
<style>
.b_pzjjb1e {
  d: path("M7.75 11h8.5A1.75 1.75 0 0 1 18 12.75v3a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 6 15.75v-3A1.75 1.75 0 0 1 7.75 11M10 11v6.5m4-6.5v6.5m-8-3.25h12");
}

.ghdle1bhl {
  d: path("M6.875 3.5h10.25A4.375 4.375 0 0 1 21.5 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 16.125v-8.25A4.375 4.375 0 0 1 6.875 3.5M2.5 8h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
