<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjl-c_moi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:popcorn" /></template>
<style>
.vjl-c_moi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 10.75h14l-1.5 9.4a1.25 1.25 0 0 1-1.25 1.1h-8.5a1.25 1.25 0 0 1-1.25-1.1Zm.5 0a2.25 2.25 0 0 1 1.25-4.5A3 3 0 0 1 12 4.5a3 3 0 0 1 5.25 1.75a2.25 2.25 0 0 1 1.25 4.5m-8.75 0l.5 10.5m4-10.5l-.5 10.5");
}

</style>
