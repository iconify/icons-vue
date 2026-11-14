<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aa3i3hb-m"/><path class="zz97p9rcy"/><path class="cjif5bwva"/><path class="zllb3kbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:table-transpose" /></template>
<style>
.aa3i3hb-m {
  d: path("M4.25 2.5h9A1.75 1.75 0 0 1 15 4.25v9A1.75 1.75 0 0 1 13.25 15h-9a1.75 1.75 0 0 1-1.75-1.75v-9A1.75 1.75 0 0 1 4.25 2.5");
}

.cjif5bwva {
  d: path("M6.75 6.5V15m4-8.5V15M2.5 10.75H15m2.5-7.25c3.5 2.5 4 10.5.5 14c-2.5 2.5-7 3.25-11.5 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zllb3kbhq {
  d: path("M8.75 18L6.5 20.25L8.75 22");
}

.zz97p9rcy {
  fill: currentColor;
  d: path("M4.25 2.5h9A1.75 1.75 0 0 1 15 4.25v.5a1.75 1.75 0 0 1-1.75 1.75h-9A1.75 1.75 0 0 1 2.5 4.75v-.5A1.75 1.75 0 0 1 4.25 2.5");
}

</style>
