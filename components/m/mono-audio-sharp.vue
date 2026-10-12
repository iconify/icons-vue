<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssis4kbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mono-audio-sharp" /></template>
<style>
.ssis4kbow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.5v-1H6.5L11 4.75v14.5L6.5 15.5H2.75v-1Zm11.5-2c2.5 0 3 4.5 5.25 4.5h1.75m-7 4.5c2.5 0 3-4.5 5.25-4.5");
}

</style>
