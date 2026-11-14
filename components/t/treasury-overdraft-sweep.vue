<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko_5f1bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treasury-overdraft-sweep" /></template>
<style>
.ko_5f1bfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5c2.5 0 3.5 8 9.5 8s7-8 9.5-8m-19 4H4m2.75 0h1.5m2.75 0h1.5m2.75 0h1.5m2.75 0H21m.5 4.5L18 16.5m.75.75l-1.5-1.5l-4.25 3l2.25 2.75Zm-3.25.5L14.25 20");
}

</style>
