<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="duu12rf5n"/><path class="wqcl8_ygf"/><path class="xxf06_b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-index-outline-thin" /></template>
<style>
.duu12rf5n {
  d: path("M10 5.5v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.wqcl8_ygf {
  d: path("M14 5.5v6");
}

.xxf06_b4i {
  d: path("M8 8.5h8");
}

</style>
