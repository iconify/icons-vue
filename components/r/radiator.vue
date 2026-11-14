<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_i6_d2qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radiator" /></template>
<style>
.w_i6_d2qx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 6h9A3.5 3.5 0 0 1 20 9.5V14a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 14V9.5A3.5 3.5 0 0 1 7.5 6M8 6v11.5M12 6v11.5M16 6v11.5m-10 3v-3m12 3v-3");
}

</style>
