<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4-rykbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:massage-gun" /></template>
<style>
.g4-rykbqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 4.5h5.5a3.25 3.25 0 0 1 3.25 3.25A3.25 3.25 0 0 1 11.25 11h-5.5A3.25 3.25 0 0 1 2.5 7.75A3.25 3.25 0 0 1 5.75 4.5M7.5 11v8.5a2 2 0 0 0 2 2h1a2 2 0 0 0 2-2V11m2-3.25H17m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
