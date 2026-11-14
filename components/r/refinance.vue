<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcelt5b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:refinance" /></template>
<style>
.rcelt5b8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5L9 3l6 4.5m-12 0h12m-12.5 2h13M2.5 20H12M4.5 9.5V18M9 9.5V18m4.5-8.5v3.6m1 2.65h6.75M19.5 14l1.75 1.75l-1.75 1.75m2 2.75h-6.75m1.75-1.75l-1.75 1.75L16.5 22");
}

</style>
