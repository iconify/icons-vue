<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq5s5jbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-cast" /></template>
<style>
.lq5s5jbaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 10.25H7a2.5 2.5 0 1 0-4 0q1.5 1.75 0 3.5a2.5 2.5 0 1 0 4 0h3.25m3.5-3.5H17a2.5 2.5 0 1 1 4 0q-1.5 1.75 0 3.5a2.5 2.5 0 1 1-4 0h-3.25M12 7.5za1.75 1.75 0 0 1 1.75 1.75v5.5A1.75 1.75 0 0 1 12 16.5a1.75 1.75 0 0 1-1.75-1.75v-5.5A1.75 1.75 0 0 1 12 7.5");
}

</style>
