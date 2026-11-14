<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j89km0bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:teeth-arch-upper" /></template>
<style>
.j89km0bss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20C3 10 6.5 3 12 3s9 7 9 17h-4.5c0-8-2-12.5-4.5-12.5S7.5 12 7.5 20Zm9-17v4.5m-6.5.25l3.25 3m9.75-3l-3.25 3");
}

</style>
