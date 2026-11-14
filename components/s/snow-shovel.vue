<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eg_ncubfn"/><path class="yavqkz_9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snow-shovel" /></template>
<style>
.eg_ncubfn {
  d: path("m5.329 19.607l3.267 1.257a1.75 1.75 0 0 0 2.269-1.026l1.257-3.392a1.75 1.75 0 0 0-1.088-2.268l-3.393-1.131a1.75 1.75 0 0 0-2.207 1.088l-1.131 3.266a1.75 1.75 0 0 0 1.026 2.206M9.25 13.75L13 3.5M11.25 3l3.5 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yavqkz_9c {
  d: path("M11.5 18c2-2.5 7-2.5 9 3.5");
}

</style>
