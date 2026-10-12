<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m25-xry7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mortar-pestle-sharp" /></template>
<style>
.m25-xry7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.49 9.57l-.98-1.14l-.66-.75l.8-.59l4.83-3.58l.8-.59l.66.76l.12.14l.66.76l-.7.72l-4.17 4.3l-.7.72zM4.25 13.5h15.5a7.75 7.75 0 0 1-15.5 0Z");
}

</style>
