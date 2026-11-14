<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8xsgk5xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:steam-pipe" /></template>
<style>
.u8xsgk5xu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15H10m4 0h7.5m-19 5H10m4 0h7.5m-9.75-7h.5A1.75 1.75 0 0 1 14 14.75v5.5A1.75 1.75 0 0 1 12.25 22h-.5A1.75 1.75 0 0 1 10 20.25v-5.5A1.75 1.75 0 0 1 11.75 13M9.5 10.25c-1.25-1.25 1.25-2.75 0-4s1.25-2.5 0-3.75m5 7.75c-1.25-1.25 1.25-2.75 0-4s1.25-2.5 0-3.75");
}

</style>
