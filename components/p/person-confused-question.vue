<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9gr-pb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-confused-question" /></template>
<style>
.z9gr-pb9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5c0-3.25 3.25-5.5 7.5-5.5s7.5 2.25 7.5 5.5c0 .6-.4 1-1 1H4c-.6 0-1-.4-1-1ZM6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM17 5a2.25 2.25 0 1 1 3.5 2.5q-1.25.5-1.25 2.25m0 2.75h.01");
}

</style>
