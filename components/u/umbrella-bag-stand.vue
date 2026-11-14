<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6k9b97am"/><path class="k-skrej7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:umbrella-bag-stand" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-skrej7y {
  d: path("M12 5.5L14.75 9L12 17.5L9.25 9Zm0 0v-1a1.75 1.75 0 0 0-3.5 0m3.5 1v12");
}

.w6k9b97am {
  d: path("M9.75 9h4.5A1.75 1.75 0 0 1 16 10.75v7a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 17.75v-7A1.75 1.75 0 0 1 9.75 9M6.5 19.5h11a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

</style>
