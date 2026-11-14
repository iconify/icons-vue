<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-1wkphlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pen-holder" /></template>
<style>
.b-1wkphlk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11h13v8a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2ZM9 11L8 3.5m4 7.5V2.5m3 8.5l1-7.5");
}

</style>
