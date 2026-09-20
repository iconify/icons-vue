<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cn4r8yd4q"/><path class="zn5d9ob7n"/><path class="yxo79mbqo"/><path class="i9l-u8avp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mutex-flow-outline-thin" /></template>
<style>
.cn4r8yd4q {
  d: path("M8.5 12a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i9l-u8avp {
  d: path("M18 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.yxo79mbqo {
  d: path("M2 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zn5d9ob7n {
  d: path("M9.5 10a2.5 2.5 0 0 1 5 0");
}

</style>
