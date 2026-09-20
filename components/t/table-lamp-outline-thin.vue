<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tu8-ndo1t"/><path class="a6tpycbpp"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:table-lamp-outline-thin" /></template>
<style>
.a6tpycbpp {
  d: path("M12 12v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.tu8-ndo1t {
  d: path("m4 12 5 -5h6l5 5Z");
}

</style>
