<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej_kg6shh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:no-hire" /></template>
<style>
.ej_kg6shh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3.5h.5A1.75 1.75 0 0 1 6.5 5.25v6.5a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-6.5A1.75 1.75 0 0 1 4.25 3.5M6.5 13l3.75 6.75c.5 1 2.75.75 2.75-1.25v-4h5.75a2 2 0 0 0 2-2.25l-1.25-7a2 2 0 0 0-2-1.75h-11Z");
}

</style>
