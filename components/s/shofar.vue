<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b7-xbqjtq"/><path class="xxub2slnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shofar" /></template>
<style>
.b7-xbqjtq {
  d: path("M11.5 5c0 6-1.5 11-7.5 13.5l.5 2.25C14 19.5 20.5 13 20.5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xxub2slnt {
  d: path("M11.5 5a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0Z");
}

</style>
