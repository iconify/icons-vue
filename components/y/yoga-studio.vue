<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvt8-5b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:yoga-studio" /></template>
<style>
.jvt8-5b9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm2.25 3v6.75m0-5L8 12l-2 3.5m6-6l4 2.5l2 3.5m-14.5 2c0-1.5 2.5-2 8.5-.5c6-1.5 8.5-1 8.5.5s-2.5 2-8.5 1c-6 1-8.5.5-8.5-1Z");
}

</style>
