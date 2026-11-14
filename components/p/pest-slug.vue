<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp-cz34uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pest-slug" /></template>
<style>
.hp-cz34uu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17h16.5a2 2 0 0 0 2-2v-4.5a3 3 0 0 0-6 0v.75c0 1.25-2.5 1.75-6 2S4 15 3 17m14-9.25L15.75 3.5M20 7.75l1.25-4.25M2.5 20.5q2-1.25 4 0t4 0t4 0");
}

</style>
