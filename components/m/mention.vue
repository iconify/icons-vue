<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s708y4als"/><path class="qkpvpo4cr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mention" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qkpvpo4cr {
  d: path("M13.75 11.1a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0m0 0v.75c0 .9.6 1.5 1.4 1.5s1.35-.6 1.35-1.5v-.75a4.5 4.5 0 1 0-1.75 3.55");
}

.s708y4als {
  d: path("M12 3.25c4.85 0 8.75 3.5 8.75 7.85s-3.9 7.85-8.75 7.85c-1.1 0-2.15-.18-3.1-.5L4.6 20c-.6.2-1.15-.4-.9-.95l1.2-2.9c-1-1.4-1.65-3.15-1.65-5.05c0-4.35 3.9-7.85 8.75-7.85");
}

</style>
