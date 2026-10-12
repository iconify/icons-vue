<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu2c1_b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-meter-sharp" /></template>
<style>
.eu2c1_b6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5h15v12.75h-15zM8.25 13h7.5m-7.5 4h3M8 4.75a5.5 5.5 0 0 1 8 0m-5.75 2L12 5.035l1.75 1.715");
}

</style>
