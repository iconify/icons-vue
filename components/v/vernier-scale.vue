<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6dl2kb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vernier-scale" /></template>
<style>
.h6dl2kb-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v7h-19ZM6 13.75h12v6.5H6ZM6 11V8m4 3V8m4 3V8m4 3V8m-9.5 5.75v3m3.5-3v3m3.5-3v3");
}

</style>
