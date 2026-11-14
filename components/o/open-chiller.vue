<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gcyp9ccho"/><path class="vp5fd2b9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:open-chiller" /></template>
<style>
.gcyp9ccho {
  d: path("M3.5 21.5V4h17v17.5m-17 0h17M3.5 7h17m-17 5.5h17M3.5 17h17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vp5fd2b9i {
  d: path("M7.25 9.5za1.25 1.25 0 0 1 1.25 1.25v.5a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 6 11.25v-.5A1.25 1.25 0 0 1 7.25 9.5m4.75 0za1.25 1.25 0 0 1 1.25 1.25v.5A1.25 1.25 0 0 1 12 12.5a1.25 1.25 0 0 1-1.25-1.25v-.5A1.25 1.25 0 0 1 12 9.5m4.75 0zA1.25 1.25 0 0 1 18 10.75v.5a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-.5a1.25 1.25 0 0 1 1.25-1.25m-9.5 4.75zA1.25 1.25 0 0 1 8.5 15.5v.25A1.25 1.25 0 0 1 7.25 17A1.25 1.25 0 0 1 6 15.75v-.25a1.25 1.25 0 0 1 1.25-1.25m7.125 0h1.75a1.375 1.375 0 0 1 1.375 1.375A1.375 1.375 0 0 1 16.125 17h-1.75A1.375 1.375 0 0 1 13 15.625a1.375 1.375 0 0 1 1.375-1.375m-8.875 5h2m3.5 0h2m3.5 0h2");
}

</style>
