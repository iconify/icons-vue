<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mtnyr1-ve"/><path class="d4huj-qnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oximeter" /></template>
<style>
.d4huj-qnn {
  d: path("M2.75 10.5h10a2 2 0 0 1 0 4h-10ZM9.5 5.25h1.75l1-1.25l1.5 2.5l1-1.25h1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mtnyr1-ve {
  d: path("M8 2.75h10.25a3 3 0 0 1 3 3v12.5a3 3 0 0 1-3 3H7.75a1.75 1.75 0 0 1 0-3.5h9a1 1 0 0 0 1-1V8.5a1 1 0 0 0-1-1H8a2.375 2.375 0 0 1 0-4.75");
}

</style>
