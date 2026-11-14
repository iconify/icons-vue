<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o07r04btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:traffic-signals-ahead" /></template>
<style>
.o07r04btx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5L7 3m7.5 18.5L10 3m8.25-.5zA2.75 2.75 0 0 1 21 5.25v5.5a2.75 2.75 0 0 1-2.75 2.75a2.75 2.75 0 0 1-2.75-2.75v-5.5a2.75 2.75 0 0 1 2.75-2.75m0 2.75h.01M18.25 8h.01m-.01 2.75h.01");
}

</style>
