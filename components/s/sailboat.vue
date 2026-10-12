<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo45uibuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sailboat" /></template>
<style>
.bo45uibuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 3.75v9.75q0 1-1 1h-5q-1 0-.49-.86l5.98-10.03q.51-.86.51.14m2.5 2v7.75q0 1 1 1h4.5q1 0 .45-.83l-5.4-8.09q-.55-.83-.55.17m-10 11h17.5l-1.6 3.4a1.75 1.75 0 0 1-1.58 1.1H6.43a1.75 1.75 0 0 1-1.58-1.1Z");
}

</style>
