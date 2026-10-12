<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msb2yhu_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slipper-sharp" /></template>
<style>
.msb2yhu_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 20.25h16.5V17.5c0-3.5-2.5-5.75-5.75-5.75c-2.5 0-4 1.25-5.25 3l-1.125 1.5H2.75v4zm6-3h8");
}

</style>
