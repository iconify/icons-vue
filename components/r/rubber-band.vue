<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3c6pmbrm"/><rect class="ur9mpkjga"/><path class="d4o_jdbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rubber-band" /></template>
<style>
.d4o_jdbce {
  d: path("M2.75 15H10l2-1.75L14 15h7.25");
}

.f3c6pmbrm {
  d: path("M8 3.25h8m-10 3h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ur9mpkjga {
  width: 16px;
  height: 11.5px;
  x: 4px;
  y: 9.25px;
  rx: 2px;
}

</style>
