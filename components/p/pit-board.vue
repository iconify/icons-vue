<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-94uhbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pit-board" /></template>
<style>
.u-94uhbhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h9A3.5 3.5 0 0 1 20 6v6a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 12V6a3.5 3.5 0 0 1 3.5-3.5m4.5 13v6m-4.5-15h9m-9 5H14");
}

</style>
