<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0tbvsbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-bowl" /></template>
<style>
.l0tbvsbsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5h19l-2.5 7H5ZM15 5H9a2 2 0 1 0-3 1.75A2 2 0 1 0 9 8.5h6a2 2 0 1 0 3-1.75A2 2 0 1 0 15 5");
}

</style>
