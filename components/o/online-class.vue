<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x4hlzsk-k"/><path class="m8zr609dv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:online-class" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8zr609dv {
  d: path("M2.75 19h18.5m-8.8-12.54l3.35 1.58q.45.21 0 .42l-3.35 1.58q-.45.21-.9 0L8.2 8.46q-.45-.21 0-.42l3.35-1.58q.45-.21.9 0m-2.7 4.04V12q2.25 1.5 4.5 0v-1.5");
}

.x4hlzsk-k {
  width: 15.5px;
  height: 11px;
  x: 4.25px;
  y: 4.25px;
  rx: 2px;
}

</style>
