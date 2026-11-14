<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7meh_seq"/><path class="zg0jnebcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tower-house" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o7meh_seq {
  d: path("m13.29 3.907l3.75 4.091a1.75 1.75 0 0 1 .46 1.183V19.75a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75V9.181a1.75 1.75 0 0 1 .46-1.183l3.75-4.091a1.75 1.75 0 0 1 2.58 0");
}

.zg0jnebcj {
  d: path("M12 10.5za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5m-1.5 11V18a1.5 1.5 0 0 1 3 0v3.5");
}

</style>
