<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q650gfmwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-headset" /></template>
<style>
.q650gfmwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7h13a3 3 0 0 1 3 3v5a3 3 0 0 1-3 3h-3L14 15.5c-.6-.9-3.4-.9-4 0L8.5 18h-3a3 3 0 0 1-3-3v-5a3 3 0 0 1 3-3");
}

</style>
