<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4p_49b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treadmill-incline" /></template>
<style>
.l4p_49b7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 20.5l16.5-5a1.5 1.5 0 0 1 1.75 1a1.5 1.5 0 0 1-1 1.5l-16.5 4Zm15.5-4.75L17.5 5M15 5h4.5m-15-1H9v4.5M4 9l5-5");
}

</style>
