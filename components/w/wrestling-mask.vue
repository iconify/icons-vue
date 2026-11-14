<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-e1bzj8r"/><path class="fy9wqjcxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wrestling-mask" /></template>
<style>
.f-e1bzj8r {
  d: path("M12 2.5c5.5 1.5 8 5 8 10c0 5.5-3.5 9-8 9s-8-3.5-8-9c0-5 2.5-8.5 8-10");
}

.fy9wqjcxf {
  d: path("m6.75 10.25l3.75 1.25l-.75 2.25l-2.25-.5Zm10.5 0L13.5 11.5l.75 2.25l2.25-.5ZM10 17.5h4m-2-15V7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
