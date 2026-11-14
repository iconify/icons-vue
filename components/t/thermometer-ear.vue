<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftffyfb9g"/><path class="qrcqgxbsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thermometer-ear" /></template>
<style>
.ftffyfb9g {
  d: path("M9.75 9c0-3.5 2.5-6 6-6c3.25 0 5.5 2.5 5.5 5.75c0 2.75-1.5 4-2.75 5.25s-1.25 2.5-1.75 4.5c-.5 1.75-2 2.5-3.5 2.5c-2 0-3.5-1.5-3.5-3.5m-5.862-4.804za2.5 2.5 0 0 1 3.205 1.494l.513 1.41a2.5 2.5 0 0 1-1.494 3.204a2.5 2.5 0 0 1-3.205-1.494l-.513-1.41a2.5 2.5 0 0 1 1.494-3.204M7.5 14l4.25-1.75M8 17l3.75-4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qrcqgxbsr {
  d: path("M12.75 9c0-1.75 1.25-3 3-3s2.75 1.25 2.75 2.75");
}

</style>
