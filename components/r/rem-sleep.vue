<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmbf53bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rem-sleep" /></template>
<style>
.bmbf53bhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13.5c4 5 14 5 18 0M7 16.25L5.75 18.5M12 17.25V20m5-3.75l1.25 2.25M14 3a4.5 4.5 0 1 0 3 6.5A3.75 3.75 0 0 1 14 3");
}

</style>
