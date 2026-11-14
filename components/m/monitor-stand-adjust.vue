<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz4z6pycb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:monitor-stand-adjust" /></template>
<style>
.tz4z6pycb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h13v10h-13ZM9 13v8m-3.5 0h7M20 6.5V14m-1.75-5.75L20 6.5l1.75 1.75m-3.5 4L20 14l1.75-1.75");
}

</style>
