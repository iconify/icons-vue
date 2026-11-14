<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hvviv1she"/><path class="qrt3ojurm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:picnic-basket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvviv1she {
  d: path("M5.548 11h12.904a1.75 1.75 0 0 1 1.729 2.023l-.948 6a1.75 1.75 0 0 1-1.728 1.477H6.495a1.75 1.75 0 0 1-1.728-1.477l-.948-6A1.75 1.75 0 0 1 5.548 11");
}

.qrt3ojurm {
  d: path("M6.5 11V9a5.5 5.5 0 0 1 11 0v2M4.25 14.75h15.5m-7.75 0v5.75");
}

</style>
