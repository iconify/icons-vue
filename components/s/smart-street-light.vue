<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewy8a4b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-street-light" /></template>
<style>
.ewy8a4b9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 21.5V7A3.5 3.5 0 0 1 10 3.5h2.5m0 0h7a3.5 3.5 0 0 1-7 0M4 21.5h5M19.25 9.129a6.5 6.5 0 0 1-6.5 0");
}

</style>
