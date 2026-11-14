<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywxyk5xpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mouse-vertical" /></template>
<style>
.ywxyk5xpj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.36 3.301za4.5 4.5 0 0 1 3.466 5.337l-1.871 8.803a4.5 4.5 0 0 1-5.337 3.466a4.5 4.5 0 0 1-3.466-5.337l1.871-8.803a4.5 4.5 0 0 1 5.337-3.466m-.727 3.423l-.624 2.935M3.5 14a1.5 3 0 1 0 3 0a1.5 3 0 1 0-3 0");
}

</style>
