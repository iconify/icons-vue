<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oh5eun6ew"/><path class="yexeb4bvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shoe-cabinet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oh5eun6ew {
  d: path("M3.75 21.25V4.75h16.5v16.5m-16.5-10h16.5m-16.5 8h16.5");
}

.yexeb4bvh {
  d: path("M6.75 11.25v-3a.5.5 0 0 1 .5-.5h1.5a2 2 0 0 0 2 1.5h3.5a2.5 2.5 0 0 1 2.5 2Zm.75 8v-3a.5.5 0 0 1 .5-.5h1.5a2 2 0 0 0 2 1.5H15a2.5 2.5 0 0 1 2.5 2Z");
}

</style>
