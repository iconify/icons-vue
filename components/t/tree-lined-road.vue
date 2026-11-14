<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhrhbwbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tree-lined-road" /></template>
<style>
.mhrhbwbwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 21.5l3-17.5m6 17.5L13.5 4m-11 3A2.25 2.25 0 1 0 7 7a2.25 2.25 0 1 0-4.5 0m2.25 2.25V17M17 7a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 17 7m2.25 2.25V17");
}

</style>
