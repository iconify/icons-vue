<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miz2apbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stream-key" /></template>
<style>
.miz2apbxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm5.25 2.25l9.25 9.25m-2-2l-1.75 1.75M16 16l-1.75 1.75M3.804 12a6 6 0 0 1 0-6M6 3.804a6 6 0 0 1 6 0");
}

</style>
