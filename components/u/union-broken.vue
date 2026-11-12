<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysnvo_v0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:union-broken" /></template>
<style>
.ysnvo_v0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 2.01733C11.4466 2.06413 10.52 2.23743 9.8787 2.87873C9 3.75743 9 5.17163 9 8.00003C9 8.55233 8.5523 9.00003 8 9.00003C5.1716 9.00003 3.7574 9.00003 2.8787 9.87873C2 10.7574 2 12.1716 2 15V16C2 18.8284 2 20.2427 2.8787 21.1213C3.7574 22 5.1716 22 8 22H9C11.8284 22 13.2426 22 14.1213 21.1213C15 20.2427 15 18.8284 15 16C15 15.4477 15.4477 15 16 15C18.8284 15 20.2426 15 21.1213 14.1213C22 13.2427 22 11.8284 22 9.00003V8.00003C22 5.17163 22 3.75743 21.1213 2.87873C20.48 2.23743 19.5534 2.06413 18 2.01733");
}

</style>
