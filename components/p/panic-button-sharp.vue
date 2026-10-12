<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3qgm0b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:panic-button-sharp" /></template>
<style>
.z3qgm0b_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.25h18.5v6H2.75zm3.25 0a6 6 0 0 1 12 0Zm6-12.5v3M5.5 5l1.75 1.75M18.5 5l-1.75 1.75");
}

</style>
