<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czenmcb5r"/><path class="b6ymi-b9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:public-shower" /></template>
<style>
.b6ymi-b9m {
  d: path("M11.5 10a4.5 4.5 0 0 1 9 0Zm1.5 3l-1 5.5m4-5.5v5.5m3-5.5l1 5.5");
}

.czenmcb5r {
  d: path("M4 21.5V6a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
