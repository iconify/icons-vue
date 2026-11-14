<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbij_fbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:squat-rack" /></template>
<style>
.mbij_fbvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21V6m12 15V6M3 21h6m6 0h6M2.5 6h19M3.75 3zA1.25 1.25 0 0 1 5 4.25v3.5A1.25 1.25 0 0 1 3.75 9A1.25 1.25 0 0 1 2.5 7.75v-3.5A1.25 1.25 0 0 1 3.75 3m16.5 0za1.25 1.25 0 0 1 1.25 1.25v3.5A1.25 1.25 0 0 1 20.25 9A1.25 1.25 0 0 1 19 7.75v-3.5A1.25 1.25 0 0 1 20.25 3");
}

</style>
