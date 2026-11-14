<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq9y74gmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signal-check" /></template>
<style>
.uq9y74gmf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5V21m3.25-7v7M9 10.5V21m3.25-14v9.6m0 2.8V21M15.5 3v11.8m-.75 3.2l2 2L21 15.75");
}

</style>
