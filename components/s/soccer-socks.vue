<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b14j7vp9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-socks" /></template>
<style>
.b14j7vp9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 2.5h4V14L10 16.5a2.25 2.25 0 0 1-1.5 4H6.25a3 3 0 0 1-3-3Zm10.5 0h4V14l2.75 2.5a2.25 2.25 0 0 1-1.5 4h-2.25a3 3 0 0 1-3-3ZM3.25 6h4m6.5 0h4");
}

</style>
