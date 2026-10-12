<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uezw9i39k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trash-bin-kitchen-sharp" /></template>
<style>
.uezw9i39k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 6.5a6.75 3.75 0 0 1 13.5 0ZM6.5 9H19l-.15 1.49l-.95 9.27l-.15 1.49H6.25l-.15-1.49l-.95-9.27L5 9zm3.5 3.25v5.5m4-5.5v5.5m4.4 1.5h2.85");
}

</style>
