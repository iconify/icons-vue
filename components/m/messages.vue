<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qk9wmmyqp"/><path class="ku_4xu5zc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:messages" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ku_4xu5zc {
  d: path("M2.75 10.25a2 2 0 0 1 2-2h8.5a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H9.5L5.85 21a.54.54 0 0 1-.85-.45v-2.3h-.25a2 2 0 0 1-2-2Z");
}

.qk9wmmyqp {
  d: path("M8.25 7.25v-1.5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v6.5a2 2 0 0 1-2 2h-.75v1.85c0 .45-.5.7-.85.45l-1.15-2.3");
}

</style>
