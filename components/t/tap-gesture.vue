<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cky4xaczd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tap-gesture" /></template>
<style>
.cky4xaczd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 16v-5.5a1.25 1.25 0 0 1 2.5 0V14H14a2.5 2.5 0 0 1 2.5 2.5v.5a4.25 4.25 0 0 1-4.25 4.25h-.75a3.75 3.75 0 0 1-3.75-3.75V17a1 1 0 0 1 1-1Zm2.5-1.5v2.25M11 6.5V4M7.94 7.93L6.02 6.32m8.04 1.61l1.92-1.61");
}

</style>
