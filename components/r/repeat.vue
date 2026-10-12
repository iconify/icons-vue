<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va3k4xeoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:repeat" /></template>
<style>
.va3k4xeoj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 11.25v-1a4 4 0 0 1 4-4h11.5M16.5 3l3.25 3.25L16.5 9.5m3.25 3.25v1a4 4 0 0 1-4 4H4.25M7.5 21l-3.25-3.25L7.5 14.5");
}

</style>
