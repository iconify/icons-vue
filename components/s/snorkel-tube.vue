<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u981__cua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snorkel-tube" /></template>
<style>
.u981__cua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 3v11.5A4.5 4.5 0 0 1 11 19H9m-2.75-2h1A1.75 1.75 0 0 1 9 18.75v.5A1.75 1.75 0 0 1 7.25 21h-1a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 6.25 17M14 3h3m-3.5 5h4");
}

</style>
