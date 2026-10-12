<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugi6sib6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:syringe-check" /></template>
<style>
.ugi6sib6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.7 13.76l4.94-4.94q.71-.71 1.42 0l2.12 2.12q.71.71 0 1.42l-4.94 4.94q-.71.71-1.42 0L6.7 15.18q-.71-.71 0-1.42m-3.19 6.73l4.25-4.25m6.36-6.36l3.54-3.54M15.71 4.4l3.89 3.89m-8.13-1.06l5.3 5.3m-5.12 3.36l-1.42-1.42m3.54-.7l-1.42-1.42");
}

</style>
