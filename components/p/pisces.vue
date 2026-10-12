<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4xlfdb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pisces" /></template>
<style>
.f4xlfdb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.75c3 2 4.5 5 4.5 8.25S8 18.25 5 20.25m14-16.5c-3 2-4.5 5-4.5 8.25s1.5 6.25 4.5 8.25M6.5 12h11");
}

</style>
