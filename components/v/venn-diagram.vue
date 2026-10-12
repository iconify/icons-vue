<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfjce3bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:venn-diagram" /></template>
<style>
.jfjce3bxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m7 0a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0M6.5 8.75a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
