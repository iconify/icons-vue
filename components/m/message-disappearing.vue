<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ioiqfubdz"/><path class="r8s-8ybkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:message-disappearing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ioiqfubdz {
  d: path("M2.5 10.5a2 2 0 0 1 2-2H14a2 2 0 0 1 2 2V16a2 2 0 0 1-2 2H9l-3.5 3v-3h-1a2 2 0 0 1-2-2Z");
}

.r8s-8ybkc {
  d: path("M8 5.75V4.5a2 2 0 0 1 2-2h9.5a2 2 0 0 1 2 2V11a2 2 0 0 1-2 2h-.75");
}

</style>
