<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ll6ldwtfk"/><path class="t87yld8cs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:watch-shop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ll6ldwtfk {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0m-12.5 9a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.t87yld8cs {
  d: path("m10.25 12.25l.5-2h2.5l.5 2m-3.5 6.5l.5 2.25h2.5l.5-2.25M12 15.5V14m3.5 1.5h1");
}

</style>
