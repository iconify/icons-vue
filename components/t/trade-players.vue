<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suqi71u9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trade-players" /></template>
<style>
.suqi71u9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M2.5 21.5c0-2.75 1.75-5 4-5s4 2.25 4 5M15 11.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M13.5 21.5c0-2.75 1.75-5 4-5s4 2.25 4 5M6.5 6q5.5-5.5 11 0m-11-2.75V6h2.75m8.25-2.75V6h-2.75");
}

</style>
