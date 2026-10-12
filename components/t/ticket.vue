<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywl_h2b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ticket" /></template>
<style>
.ywl_h2b1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75a2 2 0 0 1 2-2h14.5a2 2 0 0 1 2 2V9.5a2.5 2.5 0 0 0 0 5v1.75a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2V14.5a2.5 2.5 0 0 0 0-5Zm12.5 0v.75m0 3v1m0 3v.75");
}

</style>
