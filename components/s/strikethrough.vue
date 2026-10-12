<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrvs3nbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:strikethrough" /></template>
<style>
.xrvs3nbzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 6.75c-.55-1.85-2.35-3-4.75-3c-2.7 0-4.75 1.4-4.75 3.6c0 1.1.5 1.9 1.4 2.4m7.95 4.65c.45.55.65 1.2.65 2c0 2.3-2.1 3.85-5.25 3.85c-2.5 0-4.3-1.1-4.9-3M3.75 12h16.5");
}

</style>
