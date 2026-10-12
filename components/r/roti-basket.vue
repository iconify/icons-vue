<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t38xsh39v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roti-basket" /></template>
<style>
.t38xsh39v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11.75c0-3 3-5 6.5-5s6.5 2 6.5 5Zm-2.5 0h18l-1.6 7.75a1.75 1.75 0 0 1-1.7 1.5H6.3a1.75 1.75 0 0 1-1.7-1.5Zm.75 3h16.5M4.25 18h15.5");
}

</style>
