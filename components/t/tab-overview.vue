<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-m9iccsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tab-overview" /></template>
<style>
.m-m9iccsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 2.5h2.75A2.625 2.625 0 0 1 10.5 5.125v2.75A2.625 2.625 0 0 1 7.875 10.5h-2.75A2.625 2.625 0 0 1 2.5 7.875v-2.75A2.625 2.625 0 0 1 5.125 2.5m11 0h2.75A2.625 2.625 0 0 1 21.5 5.125v2.75a2.625 2.625 0 0 1-2.625 2.625h-2.75A2.625 2.625 0 0 1 13.5 7.875v-2.75A2.625 2.625 0 0 1 16.125 2.5m-11 11h2.75a2.625 2.625 0 0 1 2.625 2.625v2.75A2.625 2.625 0 0 1 7.875 21.5h-2.75A2.625 2.625 0 0 1 2.5 18.875v-2.75A2.625 2.625 0 0 1 5.125 13.5m11 0h2.75a2.625 2.625 0 0 1 2.625 2.625v2.75a2.625 2.625 0 0 1-2.625 2.625h-2.75a2.625 2.625 0 0 1-2.625-2.625v-2.75a2.625 2.625 0 0 1 2.625-2.625M2.5 5.5h8m3 0h8m-19 11h8m3 0h8");
}

</style>
