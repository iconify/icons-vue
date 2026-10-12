<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv37yr7hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sawhorse-sharp" /></template>
<style>
.iv37yr7hn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v4H2.75zm2.75 4l-2.75 12.5M5.5 8.75l2.75 12.5M18.5 8.75l-2.75 12.5m2.75-12.5l2.75 12.5m-14.3-6h10.1");
}

</style>
