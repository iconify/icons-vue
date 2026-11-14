<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1mr5663k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vernier-scale" /></template>
<style>
.b1mr5663k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 4h15.5a1.75 1.75 0 0 1 1.75 1.75v3.5A1.75 1.75 0 0 1 19.75 11H4.25A1.75 1.75 0 0 1 2.5 9.25v-3.5A1.75 1.75 0 0 1 4.25 4m3.5 9.75h8.5A1.75 1.75 0 0 1 18 15.5v3a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 6 18.5v-3a1.75 1.75 0 0 1 1.75-1.75M6 11V8m4 3V8m4 3V8m4 3V8m-9.5 5.75v3m3.5-3v3m3.5-3v3");
}

</style>
