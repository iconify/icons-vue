<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kz3h2lbhp"/><path class="m8-uwwp6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermometer-ear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kz3h2lbhp {
  d: path("m3.44 8.46l3.37-1.42Q7.5 6.75 8 6.38Q8.5 6 9.25 6H17q.75 0 1.28.53l.69.69q.53.53.53 1.28v.25q0 .75-.03 1.5l-.44 10.25q-.03.75-.78.75H16.5q-.75 0-.79-.75l-.42-8.25q-.04-.75-.79-.75H9.25q-.75 0-1.25-.37q-.5-.38-1.19-.67L3.44 9.04q-.69-.29 0-.58");
}

.m8-uwwp6r {
  d: path("M10.5 8.25h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1");
}

</style>
