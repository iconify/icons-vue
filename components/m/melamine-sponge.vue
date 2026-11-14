<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmdpgur-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:melamine-sponge" /></template>
<style>
.vmdpgur-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10h11a3.5 3.5 0 0 1 3.5 3.5V16a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 16v-2.5A3.5 3.5 0 0 1 6.5 10m-2-4.5c3-2.5 5 2.5 8 0s5 2.5 8 0");
}

</style>
