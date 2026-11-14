<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r9sdgebhx"/><path class="wjxvqbbcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mouth-gel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r9sdgebhx {
  d: path("M2.5 12c1.75-3 3.25-3.75 4.75-2.75c1.5-1 3-.25 4.75 2.75c-2 3.5-7.5 3.5-9.5 0m0 0H12m5.037-3h.926a1.75 1.75 0 0 1 1.736 1.524l1.043 8a1.75 1.75 0 0 1-1.735 1.976h-3.014a1.75 1.75 0 0 1-1.735-1.976l1.043-8A1.75 1.75 0 0 1 17.037 9");
}

.wjxvqbbcx {
  d: path("M17.5 5.75za1.5 1.5 0 0 1 1.5 1.5v.25A1.5 1.5 0 0 1 17.5 9A1.5 1.5 0 0 1 16 7.5v-.25a1.5 1.5 0 0 1 1.5-1.5m0-3h.01");
}

</style>
