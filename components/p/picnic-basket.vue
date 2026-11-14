<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvhdi7hkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:picnic-basket" /></template>
<style>
.nvhdi7hkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11h17L19 20.5H5Zm3 0V9a5.5 5.5 0 0 1 11 0v2M4.25 14.75h15.5m-7.75 0v5.75");
}

</style>
