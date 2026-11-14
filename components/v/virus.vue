<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk9rudbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:virus" /></template>
<style>
.rk9rudbqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0M12 6.5V3m0 14.5V21m-5.5-9H3m14.5 0H21m-5-4l2.25-2.25M8 8L5.75 5.75M16 16l2.25 2.25M8 16l-2.25 2.25M10.5 11h.01m2.99 2.5h.01");
}

</style>
