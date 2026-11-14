<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e75s8zchr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-cancer-care" /></template>
<style>
.e75s8zchr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.75 17l4.75-6.75c1-1.5 2-2.5 2-3.75a4 4 0 0 0-8 0c0 1.25 1 2.25 2 3.75L12.25 17m6 4C16.5 19.75 15 18.5 15 16.75a1.75 1.75 0 0 1 3.25-1a1.75 1.75 0 0 1 3.25 1c0 1.75-1.5 3-3.25 4.25");
}

</style>
