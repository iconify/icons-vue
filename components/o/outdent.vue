<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6q6pobts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:outdent" /></template>
<style>
.m6q6pobts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5h17m-9.5 5h9.5m-9.5 5h9.5m-17 5h17M5.75 10.25l-.728.566a1.5 1.5 0 0 0 0 2.368l.728.566A1.394 1.394 0 0 0 8 12.65v-1.3a1.394 1.394 0 0 0-2.25-1.1");
}

</style>
