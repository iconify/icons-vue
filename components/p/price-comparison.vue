<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uu-6nabys"/><path class="cc136rq3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:price-comparison" /></template>
<style>
.cc136rq3f {
  d: path("M5.5 10.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0m11-4a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uu-6nabys {
  d: path("m2.939 9.561l2.5-2.5a1.5 1.5 0 0 1 2.122 0l2.5 2.5a1.5 1.5 0 0 1 .439 1.06V19.5A1.5 1.5 0 0 1 9 21H4a1.5 1.5 0 0 1-1.5-1.5v-8.879a1.5 1.5 0 0 1 .439-1.06m11-4l2.5-2.5a1.5 1.5 0 0 1 2.122 0l2.5 2.5a1.5 1.5 0 0 1 .439 1.06V19.5A1.5 1.5 0 0 1 20 21h-5a1.5 1.5 0 0 1-1.5-1.5V6.621a1.5 1.5 0 0 1 .439-1.06");
}

</style>
