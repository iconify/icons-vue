<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nd7jz5vph"/><path class="gt9cu5ddg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volunteer-availability" /></template>
<style>
.gt9cu5ddg {
  d: path("m8.5 15.25l2.5 2.5l4.5-4.5");
}

.nd7jz5vph {
  d: path("M3.5 4.5h17V21h-17Zm0 5h17M8 2.5v4m8-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
