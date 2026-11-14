<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6hkmlgxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-croissant" /></template>
<style>
.w6hkmlgxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 18.5c-1-7 3.5-13 8.5-13s9.5 6 8.5 13c-2.5-4.5-5.5-6-8.5-6s-6 1.5-8.5 6m8.5-13v7m4.5 1.25l2-4.5m-11 4.5l-2-4.5");
}

</style>
