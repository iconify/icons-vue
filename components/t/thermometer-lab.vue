<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pclpreb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermometer-lab" /></template>
<style>
.pclpreb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.69 3.49L7.43 13.75a3.75 3.75 0 1 0 2.82 2.82L20.51 6.31a2 2 0 0 0-2.82-2.82m-2.12 2.12l1.24 1.24m-3.36.88l1.24 1.24m-3.36.88l1.24 1.24");
}

</style>
