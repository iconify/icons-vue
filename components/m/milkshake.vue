<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkmif_bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:milkshake" /></template>
<style>
.vkmif_bep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.77 7h6.46a1.75 1.75 0 0 1 1.692 2.195l-1.579 6a1.75 1.75 0 0 1-1.692 1.305h-3.302a1.75 1.75 0 0 1-1.692-1.305l-1.579-6A1.75 1.75 0 0 1 8.77 7M12 16.5V21m-3.5 0h7m-8-14c0-2.25 2-3.75 4.5-3.75s4.5 1.5 4.5 3.75m-3-3.5L16 2");
}

</style>
