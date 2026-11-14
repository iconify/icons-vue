<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u3dg_ygic"/><path class="j58c6ylnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:matcha-powder" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j58c6ylnt {
  d: path("M4 11v7.5Q4 21 6.5 21h11q2.5 0 2.5-2.5V11M4.018 5.187l6.108-2.223a1.25 1.25 0 0 1 1.603.747a1.25 1.25 0 0 1-.747 1.602L4.874 7.536a1.25 1.25 0 0 1-1.603-.747a1.25 1.25 0 0 1 .747-1.602M13 10l5.5-6.5");
}

.u3dg_ygic {
  d: path("M4 11a8 2.5 0 1 0 16 0a8 2.5 0 1 0-16 0");
}

</style>
