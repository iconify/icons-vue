<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1ommy9-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stream-schedule" /></template>
<style>
.q1ommy9-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.7 18H2.5V3.5h16v9.4m-16-4.4h16M6.75 2v3m7.5-3v3m2.25 15.5h.01m-.01-5a5 5 0 0 1 5 5");
}

</style>
