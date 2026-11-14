<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqb68_b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:race-fan" /></template>
<style>
.dqb68_b1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5c0-3.75 2.5-6 5.5-6s5.5 2.25 5.5 6Zm14 0V3M4.75 8a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM16.5 3l4.25 2.25L16.5 7.5");
}

</style>
