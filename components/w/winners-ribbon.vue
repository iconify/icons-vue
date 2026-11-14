<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fyrlk0i8z"/><path class="k7u12nbpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:winners-ribbon" /></template>
<style>
.fyrlk0i8z {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7u12nbpb {
  d: path("M8.5 14.5v7L12 19l3.5 2.5v-7M8.5 9a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
