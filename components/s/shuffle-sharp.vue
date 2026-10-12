<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhrplkbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shuffle-sharp" /></template>
<style>
.hhrplkbxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 17.25h4.536l1.214-1.7l4.98-7.1l1.187-1.712l2.083.012h2.5M17.5 4l2.75 2.75L17.5 9.5M3.75 6.75h4.536L9.5 8.45l.75 1.05m3.5 5l.75 1.05l1.214 1.7h4.536M17.5 14.5l2.75 2.75L17.5 20");
}

</style>
