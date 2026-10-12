<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1yftutzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:unit-test-sharp" /></template>
<style>
.m1yftutzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 3.75H5V12H2.75H5v8.25h2.75m8.5-16.5H19V12h2.25H19v8.25h-2.75m-7.5-8L11 14.5l4.25-4.5");
}

</style>
