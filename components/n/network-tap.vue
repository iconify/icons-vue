<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_seguxtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:network-tap" /></template>
<style>
.a_seguxtf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h7m5 0h7m-10.25-2h1.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 9.5 4.75v-.5a1.75 1.75 0 0 1 1.75-1.75M7.625 10h8.75A2.625 2.625 0 0 1 19 12.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 15.875v-3.25A2.625 2.625 0 0 1 7.625 10M12 6.5V10m0 8.5v3m-3 0h6");
}

</style>
