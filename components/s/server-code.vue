<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pa83bsd-p"/><path class="qw09ylq4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:server-code" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pa83bsd-p {
  d: path("M6.5 2.5h11A3.5 3.5 0 0 1 21 6v3a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 9V6a3.5 3.5 0 0 1 3.5-3.5M6 15.25h12a3 3 0 0 1 3 3a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3a3 3 0 0 1 3-3");
}

.qw09ylq4y {
  d: path("M9.5 5.25L7 7.5l2.5 2.25m5-4.5L17 7.5l-2.5 2.25m-8 8.5h.01");
}

</style>
