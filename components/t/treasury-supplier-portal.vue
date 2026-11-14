<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oe-0w-b0s"/><path class="tipgxvg9l"/><path class="s67v6yb4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treasury-supplier-portal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oe-0w-b0s {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v10a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17V7A3.5 3.5 0 0 1 6 3.5M2.5 7.25h19m-16.25-2h.01m2.74 0h.01");
}

.s67v6yb4n {
  d: path("M6.5 16.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m8.25 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.tipgxvg9l {
  d: path("M6.5 9.75h5a1.5 1.5 0 0 1 1.5 1.5V14a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 5 14v-2.75a1.5 1.5 0 0 1 1.5-1.5M13 11.5h3.25l2.25 2.25v1.75H13");
}

</style>
