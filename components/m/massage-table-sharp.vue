<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpn502b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:massage-table-sharp" /></template>
<style>
.rpn502b0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 9H14v1.5h3V9h3v4.5H2.75V9zM6 13.5L4 21m12.75-7.5l2 7.5M5.07 17h12.62");
}

</style>
