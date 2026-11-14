<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie6x0xbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plains" /></template>
<style>
.ie6x0xbkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19M4.5 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m.5 9.5h6.5m3 0H19m-10.5 4H16");
}

</style>
