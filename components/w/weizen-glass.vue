<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk05nv5ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weizen-glass" /></template>
<style>
.rk05nv5ox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 21h7c0-4-1-6-1-9c0-4 2.5-5.5 2.5-7.5V3H7v1.5C7 6.5 9.5 8 9.5 12c0 3-1 5-1 9");
}

</style>
