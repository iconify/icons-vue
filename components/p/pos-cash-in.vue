<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhyxazbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-cash-in" /></template>
<style>
.nhyxazbko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h10V9H3ZM8 9v1.5m7.2 4H4v-4h16v1.2m-5.9 9.8H2.5v-4h9.6m-8.1-3l-1.5 3m5-5h.01m4.49 0h.01m-5.51 7h4m7.5-5v7m-3-3l3 3l3-3");
}

</style>
