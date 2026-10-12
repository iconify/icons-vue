<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arsgznb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oil-can" /></template>
<style>
.arsgznb2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 20.25V16a5.25 5.25 0 0 1 10.5 0v4.25a1 1 0 0 1-1 1h-8.5a1 1 0 0 1-1-1m8.5-8.25L19 4.75M3.25 17h10.5M20 7.5c.75 1 1.25 1.75 1.25 2.5a1.25 1.25 0 0 1-2.5 0c0-.75.5-1.5 1.25-2.5");
}

</style>
