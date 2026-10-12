<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkrf0z-ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:towel-rail" /></template>
<style>
.fkrf0z-ph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h3.5m11.5 0h3.5m-15 0a2.5 2.5 0 0 1 2.5-2.5h6.5a2.5 2.5 0 0 1 2.5 2.5v7.5H6.25Zm0 7.5h11.5v5.5a2 2 0 0 1-2 2h-7.5a2 2 0 0 1-2-2Zm0 4.25h11.5");
}

</style>
