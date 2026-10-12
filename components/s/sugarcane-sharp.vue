<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="weiwikbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sugarcane-sharp" /></template>
<style>
.weiwikbil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4.5h3.5v16.75H6zm8.5-1.75H18v18.5h-3.5zM6 9h3.5M6 13.75h3.5M6 18h3.5m5-10.5H18m-3.5 4.75H18M14.5 17H18M6 9L3.133 7.567L2.75 4.5M18 12.25l2.463-.352l.787-3.148m-11.75 5h2.6l2.4 2");
}

</style>
