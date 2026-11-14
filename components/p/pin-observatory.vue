<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nn18yybta"/><path class="m9fy4_0ed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-observatory" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m9fy4_0ed {
  d: path("M10.5 21v-4h3v4");
}

.nn18yybta {
  d: path("M4 21v-8a8 8 0 0 1 16 0v8Zm0-8h16m-7-3l6.5-6.5");
}

</style>
