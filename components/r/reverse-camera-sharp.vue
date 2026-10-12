<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3ss984_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reverse-camera-sharp" /></template>
<style>
.r3ss984_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.5h18.5V17H2.75zM8 14.5L9.5 7m6.5 7.5L14.5 7M9 11h6m-3 6v4.25m-3.5 0h7");
}

</style>
