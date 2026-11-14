<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubrftfbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rod-tube" /></template>
<style>
.ubrftfbwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.454 18.01L14.475 5.99l3.535 3.535L5.99 21.546ZM14.121 5.636l3.536-3.535l4.242 4.242l-3.535 3.536Z");
}

</style>
