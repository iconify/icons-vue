<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymsdszb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-drop-off" /></template>
<style>
.ymsdszb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h16V8h-16ZM11.55 18h-7.8V8h13.5v3.7M10.5 8v4m7.5 2.5V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
