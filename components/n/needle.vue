<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqdt8wbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:needle" /></template>
<style>
.hqdt8wbko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.541 5.106l.353.353a1.75 1.75 0 0 1 0 2.475l-1.06 1.061a1.75 1.75 0 0 1-2.475 0l-.354-.354a1.75 1.75 0 0 1 0-2.475l1.061-1.06a1.75 1.75 0 0 1 2.475 0m-3.359 3.712l-9.9 9.9m7.779-12.021l4.242 4.242");
}

</style>
