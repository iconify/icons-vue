<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4n-0g25d"/><path class="jaj8w_bnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-crate" /></template>
<style>
.h4n-0g25d {
  d: path("M3 20.5V12c0-4 3-5.5 9-5.5S21 8 21 12v8.5Zm6-14V4h6v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jaj8w_bnk {
  d: path("M7.5 10.5h4.75A1.75 1.75 0 0 1 14 12.25v4A1.75 1.75 0 0 1 12.25 18H7.5a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 7.5 10.5m1 0V18m2.75-7.5V18");
}

</style>
