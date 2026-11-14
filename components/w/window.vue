<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8f3mccio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window" /></template>
<style>
.o8f3mccio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h9A3.5 3.5 0 0 1 20 6v9a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 15V6a3.5 3.5 0 0 1 3.5-3.5m-5 19h19M12 2.5v16m-8-8h16");
}

</style>
