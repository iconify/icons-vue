<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7wdn-bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:revenue-down" /></template>
<style>
.e7wdn-bbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5V4M7 20.5V9m4.5 11.5v-2.1m0-.3v-4.6m6.5 1V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
