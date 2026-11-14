<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilk5wqb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scene-edit" /></template>
<style>
.ilk5wqb_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.233 3h5.534a1.75 1.75 0 0 1 1.648 1.161l1.25 3.5A1.75 1.75 0 0 1 14.017 10H5.983a1.75 1.75 0 0 1-1.648-2.339l1.25-3.5A1.75 1.75 0 0 1 7.233 3M10 10v9m-4 0h5.3m7.95-5.25l2 2l-5 5l-2.5.5l.5-2.5Z");
}

</style>
