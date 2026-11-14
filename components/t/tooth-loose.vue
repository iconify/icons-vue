<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt4m7aciw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-loose" /></template>
<style>
.bt4m7aciw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4c1.5.25 1.75 1.5 2.75 1.75s1.75-.5 3.25-.25c2 .5 2.75 3 2 5.25c-.75 3-2.25 3.75-3.25 5.75L15 19.75c-.5 1-1.5 1-1.75-.25L13 16.25c-.25-1.25-1.25-1.5-2-.75l-2 3c-.75.75-1.75.25-1.5-.75v-3.5c.25-2.5-.75-4 0-6.75C8.25 5 10 3.5 12 4M4.25 9.25Q4 6.75 5.5 5m-2 7.5q0 2.5 1.25 4.25");
}

</style>
