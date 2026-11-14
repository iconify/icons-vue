<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-2lurmoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:raised-hands" /></template>
<style>
.k-2lurmoy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5V6A2.75 2.75 0 0 1 8 6v4.5l.75-.75a1.25 1.25 0 0 1 1.5 2L8 15v5.5m13.5 0V6A2.75 2.75 0 0 0 16 6v4.5l-.75-.75a1.25 1.25 0 0 0-1.5 2L16 15v5.5M5.25 3.25V8m13.5-4.75V8");
}

</style>
