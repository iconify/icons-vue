<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jiv-zk20y"/><path class="o5k6l_b4k"/><path class="pk0nmdb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paraphrase" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jiv-zk20y {
  d: path("M3.5 10V8A3.5 3.5 0 0 1 7 4.5h13.5");
}

.o5k6l_b4k {
  d: path("M18.25 2.25L20.5 4.5l-2.25 2.25M20.5 14v2a3.5 3.5 0 0 1-3.5 3.5H3.5");
}

.pk0nmdb2a {
  d: path("M5.75 17.25L3.5 19.5l2.25 2.25M7.5 10h9m-9 4h6");
}

</style>
