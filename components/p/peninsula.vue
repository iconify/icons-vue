<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8l55k3kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:peninsula" /></template>
<style>
.c8l55k3kq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5c3 0 4.5 2.5 5.5 5c1 2 3.5 2 6.5 2a2.75 2.75 0 0 1 0 5.5c-3 0-5.5.5-6.5 2S6 20.5 3 20.5Zm11 2q1.75-1.5 3.5 0t3.5 0m-7 14.25q1.75-1.5 3.5 0t3.5 0");
}

</style>
