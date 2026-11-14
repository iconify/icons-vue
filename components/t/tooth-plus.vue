<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytpexx52z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-plus" /></template>
<style>
.ytpexx52z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.123 12.223C19.563 10.867 20 9.652 20 8c0-2.5-1-4.5-3.5-4.5c-2 0-3 1-4.5 1s-2.5-1-4.5-1C5 3.5 4 5.5 4 8s1 4 1.5 6.5l1 5c.25 1.25 1.75 1.25 2 0l1-4.5c.25-1 1.25-1.5 2.5-1.5s2.25.5 2.5 1.5l.046.208M18 15v6m-3-3h6");
}

</style>
