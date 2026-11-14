<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a20uo1bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:strut" /></template>
<style>
.a20uo1bgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v2m-5.5 0h11L7 7l10 2.5L7 12l10 2.5H6.5m4.5 0h2a1.75 1.75 0 0 1 1.75 1.75v3.5A1.75 1.75 0 0 1 13 21.5h-2a1.75 1.75 0 0 1-1.75-1.75v-3.5A1.75 1.75 0 0 1 11 14.5");
}

</style>
