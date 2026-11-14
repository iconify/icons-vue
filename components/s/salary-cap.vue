<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmvcc9o5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:salary-cap" /></template>
<style>
.fmvcc9o5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8.5h9a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2a2 2 0 0 1 2-2m1.5 4h9a2 2 0 0 1 2 2a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2a2 2 0 0 1 2-2m-2.5 4h9a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2a2 2 0 0 1 2-2M2.5 6V3.5h19V6");
}

</style>
