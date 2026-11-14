<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwvq49n0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ore-stockpile" /></template>
<style>
.xwvq49n0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17.5L7.5 11A2 2 0 0 1 11 9a1.8 1.8 0 0 1 3.5.5A1.8 1.8 0 0 1 17 12l4.25 5.5m-18.75 0h19");
}

</style>
