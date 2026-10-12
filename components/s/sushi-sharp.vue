<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl1m5-b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sushi-sharp" /></template>
<style>
.zl1m5-b1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.07 11.32v-.57L3.09 9l1.66-.56L9.34 6.9L11 6.34l1.75-.04l4.84-.12l1.75-.04l.62 1.64l.2.52l.62 1.64l-1.72.3l-14.29 2.53l-1.72.3zm3.08-1.69l1.56 1.96m2.78-3.23l1.57 1.95m2.95-2.24l1.57 1.96m-8.37 4.92l8.36-1.47l2.71-.48l.81 2.63l.16.52l.81 2.63l-2.71.48l-9.84 1.73l-2.71.48l-.14-2.75l-.02-.54l-.14-2.75z");
}

</style>
