<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m6u7y-evg"/><path class="epbzygbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thorn" /></template>
<style>
.epbzygbbq {
  d: path("m8.98 16.16l3.72-1.19l-2.98-1.19m.9-2.3L8.71 8.07l2.99 1.16m1.2-2.08l3.91-.06l-2.51-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m6u7y-evg {
  d: path("M8 21q1.5-10.5 8-18");
}

</style>
