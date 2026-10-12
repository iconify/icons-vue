<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0sjrrxoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:window-sensor-sharp" /></template>
<style>
.e0sjrrxoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h12.5v18.5H2.75zm6.25 0v18.5M2.75 12h12.5M18 6.75h3.25v6H18zm0 9.5h3.25");
}

</style>
