<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eed35xszf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:proposal-sent" /></template>
<style>
.eed35xszf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8h4a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 3 18.5v-7A3.5 3.5 0 0 1 6.5 8m15-5.5l-7 3l3 1.5l1.5 3.5Zm-4 4.5l4-4.5M6 13h5m-5 4h3.5");
}

</style>
