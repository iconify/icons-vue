<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my2c22b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oxygen-tank-space-sharp" /></template>
<style>
.my2c22b6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.25h7v14h-7zm10 0h7v14h-7zM3.5 12h7m3 0h7M7 7.25v-4.5h10v4.5");
}

</style>
