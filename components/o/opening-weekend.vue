<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kovy1-byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:opening-weekend" /></template>
<style>
.kovy1-byx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19M3 3.5h7.5Q6 9 6 12t1.5 5.5H3Zm18 0h-7.5Q18 9 18 12t-1.5 5.5H21Zm-18.5 17h19");
}

</style>
