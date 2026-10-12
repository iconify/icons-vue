<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uucbwvb8s"/><rect class="ho81e6j9g"/><path class="spyivz9fa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:torah-scroll" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ho81e6j9g {
  width: 4px;
  height: 14.5px;
  x: 16.25px;
  y: 4.75px;
  rx: 2px;
}

.spyivz9fa {
  d: path("M7.75 6h8.5v12h-8.5ZM10 9h4m-4 3h4m-4 3h4M5.75 4.75v-2m12.5 2v-2m-12.5 16.5v2m12.5-2v2");
}

.uucbwvb8s {
  width: 4px;
  height: 14.5px;
  x: 3.75px;
  y: 4.75px;
  rx: 2px;
}

</style>
