<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf5ca5brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:peak-demand-sharp" /></template>
<style>
.hf5ca5brw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 17.25l4-3.75L10 16.25l4.25-9.5l3.25 6.5l3.75-3.5m-18.5 11.5h18.5M2.75 3.75H5m2.5 0h2.25m2.5 0h4m2.5 0h2.5");
}

</style>
