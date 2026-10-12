<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_ha0w66u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vaccine-vial-sharp" /></template>
<style>
.w_ha0w66u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.75h6.5v3.5h-6.5zM10 6.25h4v2l2.75.786V21.25h-9.5V9.036L10 8.25ZM7.25 13.5h9.5m-9.5 4h9.5");
}

</style>
