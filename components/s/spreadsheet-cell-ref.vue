<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zqcwkbqbx"/><path class="urxuxexkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spreadsheet-cell-ref" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.urxuxexkt {
  fill: currentColor;
  d: path("M13.75 12h2.5A1.75 1.75 0 0 1 18 13.75v2.5A1.75 1.75 0 0 1 16.25 18h-2.5A1.75 1.75 0 0 1 12 16.25v-2.5A1.75 1.75 0 0 1 13.75 12");
}

.zqcwkbqbx {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3M3 9h18M9 3v18");
}

</style>
