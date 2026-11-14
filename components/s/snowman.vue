<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o2har6bvm"/><path class="wcuxuhbah"/><path class="pbz6721xg"/><path class="dgfhqybqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snowman" /></template>
<style>
.dgfhqybqf {
  d: path("M6.5 13L3 10m14.5 3l3.5-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2har6bvm {
  d: path("M8.5 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.pbz6721xg {
  fill: currentColor;
  d: path("m16.462 5.525l.788.225a.52.52 0 0 1 0 1l-.788.225a.754.754 0 0 1-.962-.725a.754.754 0 0 1 .962-.725");
}

.wcuxuhbah {
  d: path("M6 15.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

</style>
