<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b2068qbpr"/><path class="vbu6z9guh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wash-separately" /></template>
<style>
.b2068qbpr {
  d: path("M5.772 12h12.456a2.625 2.625 0 0 1 2.562 3.194l-.833 3.75A2.625 2.625 0 0 1 17.394 21H6.606a2.625 2.625 0 0 1-2.563-2.056l-.833-3.75A2.625 2.625 0 0 1 5.772 12M8 12V8.25L5.5 9L4 6l4.5-2.75H10a2 2 0 0 0 4 0h1.5L20 6l-1.5 3l-2.5-.75V12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vbu6z9guh {
  d: path("M7.25 16.5q1.25-1.25 2.5 0t2.5 0t2.5 0t2.5 0");
}

</style>
