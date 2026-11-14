<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtin86bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sake-set" /></template>
<style>
.gtin86bjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h3L9 6.5c3.5 1.5 4 5 4 8.5v4.5a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 19.5V15c0-3.5.5-7 4-8.5ZM16 15h5.5l-1 5a1 1 0 0 1-1 1H18a1 1 0 0 1-1-1Z");
}

</style>
