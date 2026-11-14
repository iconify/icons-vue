<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xka5zpbcw"/><path class="n9cwn8zus"/><path class="dngpvwzls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:walkthrough" /></template>
<style>
.dngpvwzls {
  d: path("M16.25 8.25L18 6.5l1.75 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n9cwn8zus {
  d: path("M6.25 21v-7c0-1.5.75-2 2.25-2h8q1.5 0 1.5-1.5v-4");
}

.xka5zpbcw {
  d: path("M8.5 21H21V3H3v18h1m8-18v6.5m0 5V21");
}

</style>
