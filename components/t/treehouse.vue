<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d-g4yjbzp"/><path class="tl3kgvb6t"/><path class="zjocr2bcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:treehouse" /></template>
<style>
.d-g4yjbzp {
  d: path("M7 15a3.25 3.25 0 0 1-1.25-6.25A3.25 3.25 0 0 1 9.5 4.5a3 3 0 0 1 5 0a3.25 3.25 0 0 1 3.75 4.25A3.25 3.25 0 0 1 17 15Zm3.5 5.85V15.4q0-.4.4-.4h2.2q.4 0 .4.4v5.45q0 .4-.4.4h-2.2q-.4 0-.4-.4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tl3kgvb6t {
  d: path("M8.75 14.6v-2.7q0-.4.29-.67l2.67-2.46q.29-.27.58 0l2.67 2.46q.29.27.29.67v2.7q0 .4-.4.4h-5.7q-.4 0-.4-.4");
}

.zjocr2bcp {
  d: path("M11.25 15v-2.25h1.5V15");
}

</style>
