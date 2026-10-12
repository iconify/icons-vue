<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mriqg2i5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:now-playing-sharp" /></template>
<style>
.mriqg2i5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.71 6.55l5.58 4.65l.96.8l-.96.8l-5.58 4.65l-.96.8V5.75zM15 9.75v4.5m3-7.5v10.5m3-7v3.5");
}

</style>
