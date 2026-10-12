<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo01u8bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wave-hand" /></template>
<style>
.xo01u8bru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 14.5V8a1.25 1.25 0 0 1 2.5 0V4.75a1.25 1.25 0 0 1 2.5 0v-.5a1.25 1.25 0 0 1 2.5 0v1a1.25 1.25 0 0 1 2.5 0v7.25l1.6-1.6a1.4 1.4 0 0 1 2 2l-3.6 4.35a5.5 5.5 0 0 1-3.75 4h-.75a5.5 5.5 0 0 1-5.5-5.5Zm2.5-6V12m2.5-7v7m2.5-6.5V12m4.5-8.75C19.5 3.75 20.5 4.75 21 6M3 17.25c.4 1.2 1.3 2.25 2.5 2.75");
}

</style>
