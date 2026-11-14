<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6v0neb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speaker-id" /></template>
<style>
.z6v0neb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM3.5 21.5c0-4 2.5-6.25 6-6.25s6 2.25 6 6.25m-.75-17.25a6.5 6.5 0 0 1 0 7.5M17.25 3a9.25 9.25 0 0 1 0 10M20 2.5a12 12 0 0 1 0 11");
}

</style>
