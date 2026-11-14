<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzs7lnbgq"/><path class="h1ui4cb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:press-gallery" /></template>
<style>
.h1ui4cb_o {
  d: path("M9.5 8.5h7V12M8 21.5h8M12 16v5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzs7lnbgq {
  d: path("M4.5 5a2.5 2.5 0 0 1 5 0v7h8a2 2 0 0 1 0 4h-11a2 2 0 0 1-2-2Z");
}

</style>
