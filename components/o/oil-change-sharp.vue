<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmb1n-bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oil-change-sharp" /></template>
<style>
.dmb1n-bit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v4.5H2.75zM12 10c1.3 1.6 2 2.7 2 3.75a2 2 0 0 1-4 0c0-1.05.7-2.15 2-3.75Zm-9.25 8.5l1.5 2.75h15.5l1.5-2.75");
}

</style>
