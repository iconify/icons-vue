<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uum_d8bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:variable-plus" /></template>
<style>
.uum_d8bsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.75c-2.9 4.9-2.9 11.6 0 16.5m9-16.5c2.9 4.9 2.9 11.6 0 16.5M9.75 9l4.5 6m0-6l-4.5 6");
}

</style>
