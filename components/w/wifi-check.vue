<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqw4tccye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wifi-check" /></template>
<style>
.gqw4tccye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 18h.01m-3.546-3.536A5 5 0 0 1 13 13.67m-9.218-2.388a9.5 9.5 0 0 1 13.436 0M2.075 6.819a14 14 0 0 1 16.85 0M14.75 18l2 2L21 15.75");
}

</style>
