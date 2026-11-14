<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5nh_sbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:urban-rural" /></template>
<style>
.m5nh_sbhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5v-15A1.5 1.5 0 0 1 4 4h4.5A1.5 1.5 0 0 1 10 5.5v15m-7.5 0h19M13.75 10a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm3.75 3.75v6.75M5.25 9h2m-2 4h2");
}

</style>
