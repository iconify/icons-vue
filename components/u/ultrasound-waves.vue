<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di9m2bbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ultrasound-waves" /></template>
<style>
.di9m2bbbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h5V6h-5Zm5.944 6.012a6.5 6.5 0 0 1-6.888 0m8.694 3.581a10.5 10.5 0 0 1-10.5 0m12.057 3.71a14.5 14.5 0 0 1-13.614 0");
}

</style>
