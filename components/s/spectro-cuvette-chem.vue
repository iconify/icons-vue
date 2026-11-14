<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krnksccxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spectro-cuvette-chem" /></template>
<style>
.krnksccxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3v17a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V3m-7 4h7m-13 6h3.25m12.5 0h3.25m-2-2l2 2l-2 2");
}

</style>
