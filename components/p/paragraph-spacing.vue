<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpo9z1xwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paragraph-spacing" /></template>
<style>
.rpo9z1xwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h17m-17 4H13m-9.5 9H13m-9.5 4h17M18 7.5v9m-2-7l2-2l2 2m-4 5l2 2l2-2");
}

</style>
