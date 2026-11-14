<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_aqgeq4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stadium-seats" /></template>
<style>
.h_aqgeq4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4za2.25 2.25 0 0 1 2.25 2.25v4.5A2.25 2.25 0 0 1 5 13a2.25 2.25 0 0 1-2.25-2.25v-4.5A2.25 2.25 0 0 1 5 4m7.25 0za2.25 2.25 0 0 1 2.25 2.25v4.5A2.25 2.25 0 0 1 12.25 13A2.25 2.25 0 0 1 10 10.75v-4.5A2.25 2.25 0 0 1 12.25 4m7.25 0za2.25 2.25 0 0 1 2.25 2.25v4.5A2.25 2.25 0 0 1 19.5 13a2.25 2.25 0 0 1-2.25-2.25v-4.5A2.25 2.25 0 0 1 19.5 4m-17 12h19M5 16v5m14.5-5v5");
}

</style>
