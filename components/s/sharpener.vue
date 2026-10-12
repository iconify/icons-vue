<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="p9u2wxvww"/><path class="a5q5u0bnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sharpener" /></template>
<style>
.a5q5u0bnv {
  d: path("M12.75 9.5h5m-14.25 1h3.25q.75 0 1.42.34l2.16 1.07q.67.34 0 .68l-2.16 1.07Q7.5 14 6.75 14H3.5q-.75 0-.75-.75v-2q0-.75.75-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p9u2wxvww {
  width: 12.5px;
  height: 12px;
  x: 8.75px;
  y: 6.25px;
  rx: 2.5px;
}

</style>
