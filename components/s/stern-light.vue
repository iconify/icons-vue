<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clenaabox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stern-light" /></template>
<style>
.clenaabox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12h16l-1.5 5q-6.5 4-13 0Zm8-3.5V12m-2-5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4.5 3L7 4.75M19.5 3L17 4.75");
}

</style>
