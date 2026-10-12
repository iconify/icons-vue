<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp6c1wrmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stage-lights" /></template>
<style>
.lp6c1wrmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.5h18.5M7 3.5v3m10-3v3m-10.9 0h1.8q.6 0 .73.59l.74 3.32q.13.59-.47.59H5.1q-.6 0-.47-.59l.74-3.32q.13-.59.73-.59m10 0h1.8q.6 0 .73.59l.74 3.32q.13.59-.47.59h-3.8q-.6 0-.47-.59l.74-3.32q.13-.59.73-.59M4.75 14L3.5 21.25M9.25 14l1.25 7.25M14.75 14l-1.25 7.25M19.25 14l1.25 7.25");
}

</style>
