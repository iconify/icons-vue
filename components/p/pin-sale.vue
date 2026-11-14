<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck6lwowvk"/><path class="i4s0avbcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-sale" /></template>
<style>
.ck6lwowvk {
  d: path("M12 21.5C9 19 3.5 15 3.5 11a8.5 8.5 0 0 1 17 0c0 4-5.5 8-8.5 10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4s0avbcn {
  d: path("m9.917 7.332l1.62-.147a1.75 1.75 0 0 1 1.396.505l3.133 3.133a1.75 1.75 0 0 1 0 2.475l-1.768 1.768a1.75 1.75 0 0 1-2.475 0L8.69 11.933a1.75 1.75 0 0 1-.505-1.396l.147-1.62a1.75 1.75 0 0 1 1.585-1.585m1.199 2.784h.01");
}

</style>
