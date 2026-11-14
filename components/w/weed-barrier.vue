<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzo3qbc7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weed-barrier" /></template>
<style>
.hzo3qbc7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5v-3h19v3M4 18.5h16m-8 0V10m0 5.5c0-2.5 2-4 4.5-4c0 2.5-2 4-4.5 4m0 1c-2.5 0-4.5-1.5-4.5-4c2.5 0 4.5 1.5 4.5 4");
}

</style>
