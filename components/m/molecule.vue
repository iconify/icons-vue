<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfm5k9byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:molecule" /></template>
<style>
.kfm5k9byl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16a3 3 0 1 0 6 0a3 3 0 1 0-6 0M9 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0m6.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-8-2.5l2.5-3m4 0l2.5 3");
}

</style>
