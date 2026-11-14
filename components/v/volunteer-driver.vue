<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yn1e-9b5l"/><path class="roo0v-s8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:volunteer-driver" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.roo0v-s8o {
  d: path("M5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.yn1e-9b5l {
  d: path("M2.5 12.75v-.43a1.75 1.75 0 0 1 1.269-1.683l1.534-.438a1.75 1.75 0 0 0 1.049-.833L8 6.4a1.75 1.75 0 0 1 1.53-.9h4.614a1.75 1.75 0 0 1 1.381.676l2.65 3.406a1.75 1.75 0 0 0 .828.586l1.3.433a1.75 1.75 0 0 1 1.197 1.66v.489a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75M6 10h12.5M12 5.5V10");
}

</style>
