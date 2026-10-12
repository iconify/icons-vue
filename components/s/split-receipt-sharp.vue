<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxphtsbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:split-receipt-sharp" /></template>
<style>
.jxphtsbxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h8v18.5l-2.5-1.5l-2.5 1.5l-2.5-1.5l-2.5 1.5V2.75zm1 5h4m-4 3.5h2.5m6.25.75h2L20 7.5M16.5 12l3.5 4.5m-2.5-9H20V10m-2.5 6.5H20V14");
}

</style>
