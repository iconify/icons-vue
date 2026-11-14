<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmmmou7pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:round-clothes-rack" /></template>
<style>
.jmmmou7pl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5v18m-1 0H9m-5.5-18h18M8 3.5v1.75M5.75 6.5l1.5-1.25h1.5l1.5 1.25l-.5 2l-.5-.25V13h-2.5V8.25l-.5.25Zm7.75-3v1.75M11.25 6.5l1.5-1.25h1.5l1.5 1.25l-.5 2l-.5-.25V13h-2.5V8.25l-.5.25Zm7.75-3v1.75M16.75 6.5l1.5-1.25h1.5l1.5 1.25l-.5 2l-.5-.25V13h-2.5V8.25l-.5.25Z");
}

</style>
