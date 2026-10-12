<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go8cyrwje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zoning-map-sharp" /></template>
<style>
.go8cyrwje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75zm7.25 0v18.5M10 13h11.25M2.75 9H10m2.5 1.5l6-6m-2.75 6l3-3m-6.25-.25l2.5-2.5");
}

</style>
