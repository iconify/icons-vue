<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b626vnbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:queue-music" /></template>
<style>
.b626vnbwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6h9m-9 5h9m-9 5h5m2.5 2a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0V6l4.5 1.5");
}

</style>
