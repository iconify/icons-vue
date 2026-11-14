<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kebju1mox"/><path class="exzvuzb8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:starfield" /></template>
<style>
.exzvuzb8r {
  d: path("m14.5 7.5l.263.788a1.5 1.5 0 0 0 .949.949l.788.263a.527.527 0 0 1 0 1l-.788.263a1.5 1.5 0 0 0-.949.949l-.263.788a.527.527 0 0 1-1 0l-.263-.788a1.5 1.5 0 0 0-.949-.949L11.5 10.5a.527.527 0 0 1 0-1l.788-.263a1.5 1.5 0 0 0 .949-.949L13.5 7.5a.527.527 0 0 1 1 0m-7 0h.01m-.51 8a1 1 0 1 0 2 0a1 1 0 1 0-2 0m9.5 1.5h.01m-4.51.75h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kebju1mox {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3");
}

</style>
