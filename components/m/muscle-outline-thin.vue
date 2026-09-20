<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe66no8-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:muscle-outline-thin" /></template>
<style>
.fe66no8-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21v-5c0 -4 4 -7 8 -5 1 0.5 2 1.5 2 3V9c0 -3 3 -5 5 -3s2 6 1 9 -3 6 -7 6Z");
}

</style>
