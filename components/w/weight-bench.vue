<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu_gg0b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weight-bench" /></template>
<style>
.uu_gg0b6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 11h15a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 12.5A1.5 1.5 0 0 1 4.5 11M6 14v7m12-7v7M4 21h4m8 0h4M7 3.5zA1.5 1.5 0 0 1 8.5 5v2A1.5 1.5 0 0 1 7 8.5A1.5 1.5 0 0 1 5.5 7V5A1.5 1.5 0 0 1 7 3.5m10 0zA1.5 1.5 0 0 1 18.5 5v2A1.5 1.5 0 0 1 17 8.5A1.5 1.5 0 0 1 15.5 7V5A1.5 1.5 0 0 1 17 3.5M8.5 6h7");
}

</style>
