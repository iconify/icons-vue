<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2lfdmb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sim-handbrake" /></template>
<style>
.f2lfdmb2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5h17M6 21.5v-3a4 4 0 0 1 8 0v3m-4-7l3.5-5.25m1.984-6.906l3.032 1.75l-3.5 6.062l-3.032-1.75Z");
}

</style>
