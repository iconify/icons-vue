<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4xqy2b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-leader" /></template>
<style>
.h4xqy2b-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-3 11c0-3.5 2.5-5.25 5.5-5.25s5.5 1.75 5.5 5.25M3.5 6A1.75 1.75 0 1 0 7 6a1.75 1.75 0 1 0-3.5 0M2 13.75a3.25 3.25 0 0 1 4.875-2.815M17 6a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 17 6m.125 4.935A3.25 3.25 0 0 1 22 13.75");
}

</style>
