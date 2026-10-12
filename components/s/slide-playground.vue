<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-q4b2bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slide-playground" /></template>
<style>
.h-q4b2bxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 21.25V3.75m4 17.5V3.75M4.25 8h4m-4 4.25h4m-4 4.25h4m0-9.75h1.5c1.5 0 2.5.75 3.25 2L18 18c.6 1.1 1.5 1.75 3.25 1.75");
}

</style>
