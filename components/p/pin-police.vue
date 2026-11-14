<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jcf_l5blw"/><path class="zjjbwsbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-police" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcf_l5blw {
  d: path("M5.5 17.5V14L3 10c0-3.5 4.5-5.5 9-5.5s9 2 9 5.5l-2.5 4v3.5Zm0-3.5h13m-13 3.5q6.5 5 13 0");
}

.zjjbwsbmm {
  fill: currentColor;
  d: path("M10.5 9.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
