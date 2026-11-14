<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_ddi0biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sound-direction" /></template>
<style>
.k_ddi0biy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12h.01m2.561-3.064a4 4 0 0 1 0 6.128m2.571-9.192a8 8 0 0 1 0 12.256M15.5 12H21m-3-3l3 3l-3 3");
}

</style>
