<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybhz29vem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:puzzle" /></template>
<style>
.ybhz29vem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 7.25h2.5a2.5 2.5 0 1 1 4.5 0h2.5a2 2 0 0 1 2 2v2.5a2.5 2.5 0 1 1 0 4.5v2.5a2 2 0 0 1-2 2h-9.5a2 2 0 0 1-2-2v-9.5a2 2 0 0 1 2-2");
}

</style>
