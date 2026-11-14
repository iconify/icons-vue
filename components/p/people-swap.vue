<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnk858bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:people-swap" /></template>
<style>
.gnk858bdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM2 21.5v-2C2 17.25 3.75 16 6 16s4 1.25 4 3.5v2m4 0v-2c0-2.25 1.75-3.5 4-3.5s4 1.25 4 3.5v2M5.25 4L6 6l2-1.25M6 6c1.5-4.25 10.5-4.25 12 0m-2-1.25L18 6l.75-2");
}

</style>
