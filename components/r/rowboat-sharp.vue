<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu6xn6brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rowboat-sharp" /></template>
<style>
.bu6xn6brt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.5h18.5c-.75 3.25-3 5.75-6 5.75h-6.5c-3 0-5.25-2.5-6-5.75ZM8 14h8M3.5 8h11m1-1.25H21v2.5h-6.5v-2.5z");
}

</style>
