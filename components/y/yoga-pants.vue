<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wngd4js4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:yoga-pants" /></template>
<style>
.wngd4js4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.5h8.5A1.75 1.75 0 0 1 18 4.25A1.75 1.75 0 0 1 16.25 6h-8.5A1.75 1.75 0 0 1 6 4.25A1.75 1.75 0 0 1 7.75 2.5M7 6l.5 15.5h2.75l1.75-11l1.75 11h2.75L17 6");
}

</style>
