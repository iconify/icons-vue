<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z74c0xbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:text-to-columns" /></template>
<style>
.z74c0xbhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 6h2.25A2.625 2.625 0 0 1 10 8.625v3.75A2.625 2.625 0 0 1 7.375 15h-2.25A2.625 2.625 0 0 1 2.5 12.375v-3.75A2.625 2.625 0 0 1 5.125 6m11.5 0h2.25A2.625 2.625 0 0 1 21.5 8.625v3.75A2.625 2.625 0 0 1 18.875 15h-2.25A2.625 2.625 0 0 1 14 12.375v-3.75A2.625 2.625 0 0 1 16.625 6M12 4.5V6m0 2.5V10m0 2.5V14m0 2.5V18m-7.25-7.5h3m8.5 0h3M9.75 20H4m2-2l-2 2l2 2m8.25-2H20m-2-2l2 2l-2 2");
}

</style>
