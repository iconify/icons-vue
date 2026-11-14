<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f373b2bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wine-glass-pair" /></template>
<style>
.f373b2bjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h7C10.5 9 9 12 7 12S3.5 9 3.5 3.5ZM7 12v7m-2.5 0h5m4-15.5h7C20.5 9 19 12 17 12s-3.5-3-3.5-8.5ZM17 12v7m-2.5 0h5");
}

</style>
