<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrzioc65q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monument" /></template>
<style>
.mrzioc65q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 21.25V6.5a1 1 0 0 1 1-1h14.5a1 1 0 0 1 1 1v14.75h-4.5V16a3.75 3.75 0 0 0-7.5 0v5.25ZM3.75 9h16.5M2.75 3h18.5");
}

</style>
