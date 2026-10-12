<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm7pnxo2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scan" /></template>
<style>
.jm7pnxo2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 8V5.75a2.5 2.5 0 0 1 2.5-2.5H8m8 0h2.25a2.5 2.5 0 0 1 2.5 2.5V8m0 8v2.25a2.5 2.5 0 0 1-2.5 2.5H16m-8 0H5.75a2.5 2.5 0 0 1-2.5-2.5V16m.5-4h16.5");
}

</style>
