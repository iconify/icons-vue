<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf9ybzbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ssh-key" /></template>
<style>
.xf9ybzbkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5H12a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 12 7.5H4.25A1.75 1.75 0 0 1 2.5 5.75v-1.5A1.75 1.75 0 0 1 4.25 2.5m0 7.75H12A1.75 1.75 0 0 1 13.75 12v1.5A1.75 1.75 0 0 1 12 15.25H4.25A1.75 1.75 0 0 1 2.5 13.5V12a1.75 1.75 0 0 1 1.75-1.75M5.5 5h.01m-.01 7.75h.01M14.5 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.25-1.75l3-3M20 16l1.75 1.75");
}

</style>
