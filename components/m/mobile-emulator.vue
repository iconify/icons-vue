<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-uukabxj"/><path class="jfufjrb5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mobile-emulator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfufjrb5v {
  d: path("M10.5 5.25h3A1.75 1.75 0 0 1 15.25 7v5.5a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75V7a1.75 1.75 0 0 1 1.75-1.75m.25 6.25h2.5");
}

.r-uukabxj {
  d: path("M5.5 2.5h13A3.5 3.5 0 0 1 22 6v7.5a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 13.5V6a3.5 3.5 0 0 1 3.5-3.5M12 17v4m-4 0h8");
}

</style>
