<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggmjo_btt"/><path class="oz3yj1f-u"/><path class="zw4-3ycwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:newborn-screening" /></template>
<style>
.ggmjo_btt {
  d: path("M7.5 11.5c2.75-.75 5.5-.25 5.5 2.5c.25 2.25-1 3.75-1 5.25c-.25 1.5-1.25 2.25-2.75 2S7 20 7 18.75c-.25-2-1.5-3.25-1.5-5c0-1.25.75-2 2-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oz3yj1f-u {
  fill: currentColor;
  d: path("M5.5 7.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M9 6.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m2.25.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m2 1.5a.5.5 0 1 0 1 0a.5.5 0 1 0-1 0");
}

.zw4-3ycwx {
  d: path("M17.5 13c1.25 1.5 2.25 2.75 2.25 4c0 1.4-1 2.5-2.25 2.5s-2.25-1.1-2.25-2.5c0-1.25 1-2.5 2.25-4");
}

</style>
