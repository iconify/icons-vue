<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqlz3zb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sunscreen-kids" /></template>
<style>
.wqlz3zb8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.5h9v2.75h-9Zm.75 2.75L5.75 15.5h5L12 5.25M5 15.5h6.5v6H5Zm7.765-10.946a5.5 5.5 0 0 1 1.985 10.209M17.75 4L19 2.75M20.25 10h1.5m-4 6L19 17.25");
}

</style>
