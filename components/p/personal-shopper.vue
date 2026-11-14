<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qt2xaxx-d"/><path class="sajda5xjk"/><path class="bkyl4ww6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:personal-shopper" /></template>
<style>
.bkyl4ww6w {
  d: path("m16.25 16.75l.75-2.5h2l.75 2.5M16 19.5h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qt2xaxx-d {
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-4 14c0-4 3.5-6.5 8-6.5q.657 0 1.282.07");
}

.sajda5xjk {
  fill: currentColor;
  d: path("M16.157 16.75h3.686a1.5 1.5 0 0 1 1.492 1.649l-.2 2a1.5 1.5 0 0 1-1.492 1.351h-3.286a1.5 1.5 0 0 1-1.492-1.351l-.2-2a1.5 1.5 0 0 1 1.492-1.649");
}

</style>
