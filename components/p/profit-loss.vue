<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k16-0jb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:profit-loss" /></template>
<style>
.k16-0jb4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12h18.5M8 10.25v-6.5M5.25 6.5L8 3.75l2.75 2.75M16 13.75v6.5m-2.75-2.75L16 20.25l2.75-2.75");
}

</style>
