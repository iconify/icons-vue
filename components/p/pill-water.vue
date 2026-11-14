<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sadsropaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pill-water" /></template>
<style>
.sadsropaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8L7 21.5h10L18.5 8M6.25 14.75h11.5M9.906 3.884l2.819-1.026a2 2 0 0 1 2.564 1.195a2 2 0 0 1-1.195 2.563l-2.819 1.026a2 2 0 0 1-2.564-1.195a2 2 0 0 1 1.195-2.563");
}

</style>
