<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di27vj9md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vegetable-patch" /></template>
<style>
.di27vj9md {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11h16l-3 9h-16Zm2 0V7m0 0L6 4.75M7.5 7L9 4.75M13.5 11V7m0 0L12 4.75M13.5 7L15 4.75M19.5 11V7m0 0L18 4.75M19.5 7L21 4.75");
}

</style>
