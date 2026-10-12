<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wcklgubij"/><path class="f9cmb3los"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:post-office" /></template>
<style>
.f9cmb3los {
  d: path("M9 11.75h6A1.25 1.25 0 0 1 16.25 13v4A1.25 1.25 0 0 1 15 18.25H9A1.25 1.25 0 0 1 7.75 17v-4A1.25 1.25 0 0 1 9 11.75m-.75.75L12 15.25l3.75-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wcklgubij {
  d: path("m4.27 8.52l6.71-4.79q1.02-.73 2.04 0l6.71 4.79q1.02.73 1.02 1.98V20q0 1.25-1.25 1.25h-15q-1.25 0-1.25-1.25v-9.5q0-1.25 1.02-1.98");
}

</style>
