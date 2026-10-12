<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ourwbtb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stairs-sharp" /></template>
<style>
.ourwbtb3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 21.25h-1v-4H7.5v-4.5h4.75v-4.5H17v-4.5h4.25v17.5h-1Zm-1-7.5L13.5 3.5");
}

</style>
