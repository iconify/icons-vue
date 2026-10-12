<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smd44achg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:room-service" /></template>
<style>
.smd44achg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 11.25a6.75 6.75 0 0 1 13.5 0ZM12 4.5V3M2.75 13.75h18.5m-16 0v7.5m13.5-7.5v7.5m-13.5-3.5h13.5");
}

</style>
