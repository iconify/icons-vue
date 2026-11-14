<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o899euszr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ping-pong-robot" /></template>
<style>
.o899euszr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5h4a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 10 14H6a3.5 3.5 0 0 1-3.5-3.5v-2A3.5 3.5 0 0 1 6 5m2 0V2.5M8 14v6m-3.5 0h7m4.75-10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-10.5 0h.01m4.49 0h.01");
}

</style>
