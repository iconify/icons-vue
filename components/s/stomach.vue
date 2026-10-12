<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y6_y1kbyp"/><path class="rvdvo3b0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stomach" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rvdvo3b0k {
  d: path("M15 10.75c1.5.75 2.5 2.25 2.25 4");
}

.y6_y1kbyp {
  d: path("M14.5 2.75v3.5c0 .8.5 1.25 1.25 1.5c2.5.75 4.5 2.75 4.5 6c0 4.25-3.75 7.5-8.5 7.5c-3 0-5.5-1.25-7-3.25c-.75-1-.5-2.25.5-2.75s2-.25 2.75.5c1 1 2.25 1.5 3.75 1.25c2-.35 3-2 2.25-3.75c-.5-1.25-1.75-1.5-2.75-1.75C10 11.2 9.5 10.25 9.5 9.25v-6.5Z");
}

</style>
