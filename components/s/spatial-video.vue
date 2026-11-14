<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j3isxdbfc"/><path class="sqfq43axm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spatial-video" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3isxdbfc {
  d: path("M6 7h8a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 14 18H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 7");
}

.sqfq43axm {
  d: path("M6 7V6a2 2 0 0 1 2-2h11.5a2 2 0 0 1 2 2v6.5a2 2 0 0 1-2 2h-2m-7.277-3.527l.387.213a1.5 1.5 0 0 1 0 2.628l-.387.213A1.5 1.5 0 0 1 8 12.713v-.426a1.5 1.5 0 0 1 2.223-1.314");
}

</style>
