<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxrqizl-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mannequin-head" /></template>
<style>
.fxrqizl-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c2.5 0 4 2 4 4.5s-1.25 4.25-3.25 4.75h-1.5C9.25 11.25 8 9.5 8 7s1.5-4.5 4-4.5m-1.5 9V14m3-2.5V14m-3 0C8 14.5 6 15.5 6 17.25h12c0-1.75-2-2.75-4.5-3.25M12 17.25v4.25m-3.5 0h7");
}

</style>
