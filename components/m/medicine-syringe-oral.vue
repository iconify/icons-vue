<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2_os-egp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medicine-syringe-oral" /></template>
<style>
.p2_os-egp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.303 3.868l2.829 2.829m-1.414-1.415l-1.415 1.415m-.53-.531l1.061 1.061a1.75 1.75 0 0 1 0 2.475l-4.597 4.596a1.75 1.75 0 0 1-2.474 0l-1.061-1.061a1.75 1.75 0 0 1 0-2.474l4.596-4.597a1.75 1.75 0 0 1 2.475 0m-6.541 7.602l-1.414 1.414M6.25 16S4.5 18 4.5 19.25a1.75 1.75 0 0 0 3.5 0C8 18 6.25 16 6.25 16");
}

</style>
