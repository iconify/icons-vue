<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq23c5you"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spice-rack-sharp" /></template>
<style>
.xq23c5you {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25v18m18.5-18v18m-18.5-1h18.5m-15.75-10h5v10h-5zm8 0h5v10h-5zm-7-2.75h3m5 0h3");
}

</style>
