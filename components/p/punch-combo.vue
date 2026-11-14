<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbsjrvbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:punch-combo" /></template>
<style>
.kbsjrvbwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5h8.5m-2.25-2.25L20.5 4.5l-2.25 2.25M7.5 12h13m-2.25-2.25L20.5 12l-2.25 2.25M3 19.5h17.5m-2.25-2.25l2.25 2.25l-2.25 2.25");
}

</style>
