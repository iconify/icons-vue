<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmsw8_bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swap-diagonal" /></template>
<style>
.bmsw8_bfe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.75h15.5m-3.5-3.5l3.5 3.5l-3.5 3.5m3.5 5H4.25m3.5-3.5l-3.5 3.5l3.5 3.5");
}

</style>
