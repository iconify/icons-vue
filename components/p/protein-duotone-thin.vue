<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w5h1e7d9p"/><path class="qo06t-bje"/><path class="qvytntb8g"/><path class="c7z9o8buo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:protein-duotone-thin" /></template>
<style>
.c7z9o8buo {
  d: path("M7 15h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qo06t-bje {
  d: path("M7 21V8l2 -2h6l2 2v13Z");
}

.qvytntb8g {
  d: path("M7 10h10");
}

.w5h1e7d9p {
  fill: currentColor;
  d: path("M7 21V8l2 -2h6l2 2v13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
