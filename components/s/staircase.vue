<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7e88_jdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:staircase" /></template>
<style>
.i7e88_jdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.65V18.1q0-.6.6-.6h4.8q.6 0 .6-.6v-2.55q0-.6.6-.6h4.8q.6 0 .6-.6V10.6q0-.6.6-.6h5.3q.6 0 .6.6v10.05q0 .6-.6.6H3.35q-.6 0-.6-.6m3-3.15v-5.25m6 1.5V9m6 1V5.75m-14 7.58l16-8.66");
}

</style>
