<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkb58bblb"/><path class="gsw2hh7wb"/><path class="tdbz56bir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:order-return" /></template>
<style>
.gsw2hh7wb {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v2.75M15 17h4a2 2 0 0 1 0 4h-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tdbz56bir {
  d: path("M16.5 15.5L15 17l1.5 1.5");
}

.tkb58bblb {
  d: path("M12 2.5L20.5 7v5.25H14a2 2 0 0 0-2 2v7.25L3.5 17V7Z");
}

</style>
