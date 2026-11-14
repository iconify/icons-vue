<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9daq7b6k"/><path class="rkn6z-b1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:victim-support" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9daq7b6k {
  d: path("m12 16l-5.25-5.25A3.5 3.5 0 0 1 12 6.5a3.5 3.5 0 0 1 5.25 4.25Z");
}

.rkn6z-b1f {
  d: path("M20.227 14.25a9.5 9.5 0 0 1-16.454 0");
}

</style>
