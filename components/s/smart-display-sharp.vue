<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkc61bb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-display-sharp" /></template>
<style>
.kkc61bb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.25h16.5V14.5H3.75zm3.5 4h5m-5 3h3M6.5 17h12l.38.92l.99 2.41l.38.92H3.75l.38-.92l.99-2.41l.38-.92z");
}

</style>
