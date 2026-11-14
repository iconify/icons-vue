<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g53uazb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spreader-drop" /></template>
<style>
.g53uazb0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h13L13 11H6ZM13 11l4.5 6.5m-3 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-7-2.5h.01m3.99 0h.01M9.5 19.5h.01");
}

</style>
