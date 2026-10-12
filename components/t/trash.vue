<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcv76wb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trash" /></template>
<style>
.qcv76wb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 6.25l.85 12.2a2 2 0 0 0 2 1.8h6.8a2 2 0 0 0 2-1.8l.85-12.2Zm-2 0h16.5M9 6.25v-1.5a1.5 1.5 0 0 1 1.5-1.5h3a1.5 1.5 0 0 1 1.5 1.5v1.5m-4.75 4.5v5m3.5-5v5");
}

</style>
