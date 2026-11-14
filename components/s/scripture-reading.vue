<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdz8eobso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scripture-reading" /></template>
<style>
.vdz8eobso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.5C10 4 6 3.5 2.5 4v12.5C6 16 10 16.5 12 18c2-1.5 6-2 9.5-1.5V4C18 3.5 14 4 12 5.5m0 0V18m0 0l-1.5 3l1.5-1l1.5 1Z");
}

</style>
