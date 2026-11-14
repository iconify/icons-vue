<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zz3ijbcpf"/><path class="rxpm5ub7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:script-pages" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rxpm5ub7n {
  d: path("M6.5 2.5h12a2 2 0 0 1 2 2v14m-14-9H14m-5.5 4H14m-5.5 4h4");
}

.zz3ijbcpf {
  d: path("M7 5.5h6.5A3.5 3.5 0 0 1 17 9v9a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V9A3.5 3.5 0 0 1 7 5.5");
}

</style>
