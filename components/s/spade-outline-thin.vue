<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzm42kydi"/><path class="b58isb55w"/><path class="vrecxx6kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spade-outline-thin" /></template>
<style>
.b58isb55w {
  d: path("M12 6v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vrecxx6kh {
  d: path("M9 6h6");
}

.xzm42kydi {
  d: path("M8 13h8v4l-4 4 -4 -4Z");
}

</style>
