<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ed_6s8b6d"/><path class="fb1beqbdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:virtual-tour-360" /></template>
<style>
.ed_6s8b6d {
  d: path("m6.013 9.487l4.75-4.75a1.75 1.75 0 0 1 2.474 0l4.75 4.75a1.75 1.75 0 0 1 .513 1.238v7.525A1.75 1.75 0 0 1 16.75 20h-9.5a1.75 1.75 0 0 1-1.75-1.75v-7.525a1.75 1.75 0 0 1 .513-1.238");
}

.fb1beqbdq {
  d: path("M3 13.5a9.5 3.5 0 1 0 17.5-.75M18.25 12l2.25.75l.25-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
