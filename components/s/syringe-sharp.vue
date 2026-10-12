<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vva0jobiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:syringe-sharp" /></template>
<style>
.vva0jobiu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.7 13.76l4.94-4.94l.71-.71l.71.71l2.12 2.12l.71.71l-.71.71l-4.94 4.94l-.71.71l-.71-.71l-2.12-2.12l-.71-.71zm-3.19 6.73l4.25-4.25m6.36-6.36l3.54-3.54M15.71 4.4l3.89 3.89m-8.13-1.06l5.3 5.3m-5.12 3.36l-1.42-1.42m3.54-.7l-1.42-1.42");
}

</style>
