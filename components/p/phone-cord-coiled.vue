<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoq24riab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-cord-coiled" /></template>
<style>
.hoq24riab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17c2.5 0 5-4 5-7.5C8 7 6 7 6 9.5C6 13 8.5 17 11 17s5-4 5-7.5c0-2.5-2-2.5-2 0c0 3.5 2.5 7.5 5 7.5m0 0h2.5m-19 0H3");
}

</style>
