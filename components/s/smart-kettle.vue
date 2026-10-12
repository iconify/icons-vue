<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_vt0jb5q"/><path class="hxyj34brl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-kettle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxyj34brl {
  d: path("M8.5 9.5V8a3.5 3.5 0 0 1 7 0v1.5M5.25 14.25l-2.5-2.75m2.75 1.75h13");
}

.i_vt0jb5q {
  d: path("M6.25 21.25h11.5a1.5 1.5 0 0 0 1.5-1.6l-.6-6.9a3.75 3.75 0 0 0-3.75-3.5H9.1a3.75 3.75 0 0 0-3.75 3.5l-.6 6.9a1.5 1.5 0 0 0 1.5 1.6");
}

</style>
