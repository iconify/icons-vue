<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-_-jub7s"/><path class="f2ool0qub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stump-grinder" /></template>
<style>
.f2ool0qub {
  d: path("M4.5 15.5a6 2 0 1 0 12 0a6 2 0 1 0-12 0m9.375-8.875l-.186.186a1.5 1.5 0 0 0-.439 1.06V8a.75.75 0 0 1-.75.75h-.129a1.5 1.5 0 0 0-1.06.439l-.186.186a.884.884 0 0 1-1.25 0l-.186-.186a1.5 1.5 0 0 0-1.06-.439H8.5A.75.75 0 0 1 7.75 8v-.129a1.5 1.5 0 0 0-.439-1.06l-.186-.186a.884.884 0 0 1 0-1.25l.186-.186a1.5 1.5 0 0 0 .439-1.06V4a.75.75 0 0 1 .75-.75h.129a1.5 1.5 0 0 0 1.06-.439l.186-.186a.884.884 0 0 1 1.25 0l.186.186a1.5 1.5 0 0 0 1.06.439h.129a.75.75 0 0 1 .75.75v.129a1.5 1.5 0 0 0 .439 1.06l.186.186a.884.884 0 0 1 0 1.25M10.5 6h.01m3.99 0h4l2.5 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-_-jub7s {
  d: path("M4.5 15.5v4l-1.5 2h15l-1.5-2v-4");
}

</style>
