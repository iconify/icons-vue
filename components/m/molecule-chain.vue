<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as3h_p_jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:molecule-chain" /></template>
<style>
.as3h_p_jm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5-6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5-6a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5.75 13.5l2.5-3m2.5 0l2.5 3m2.5 0l2.5-3");
}

</style>
