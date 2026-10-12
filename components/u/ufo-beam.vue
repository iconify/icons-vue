<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t06rc_b9u"/><path class="t2dno2i3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ufo-beam" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t06rc_b9u {
  d: path("M9 6a3 3 0 0 1 6 0Z");
}

.t2dno2i3e {
  d: path("M3.25 9a8.75 3 0 1 0 17.5 0a8.75 3 0 1 0-17.5 0m7.5 5.5h2.5q1 0 1.58.82l3.59 5.11q.58.82-.42.82H6q-1 0-.42-.82l3.59-5.11q.58-.82 1.58-.82");
}

</style>
