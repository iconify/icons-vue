<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuml7dubs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tax-rate" /></template>
<style>
.vuml7dubs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12L8 5.5h11.5a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H8Zm9 3.5l6-7m-5.5.75h.01m4.99 5.5h.01");
}

</style>
