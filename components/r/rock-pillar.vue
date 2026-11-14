<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ysay3qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rock-pillar" /></template>
<style>
.p9ysay3qq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 21l1-6l-.75-5.5l1.25-5l3-1.5L15 4.5l.75 5.5l-.75 5.5l1 5.5M3.5 21h17M8.75 12.5l3.25.75");
}

</style>
