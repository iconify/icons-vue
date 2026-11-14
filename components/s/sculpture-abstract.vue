<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yltnnqucz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sculpture-abstract" /></template>
<style>
.yltnnqucz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 17.5h6.5A1.75 1.75 0 0 1 17 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m.75 0c-5.5-4.5-5-14 2-14c6 0 7.5 6.5 2.5 9C11 14 10 11 12.5 9");
}

</style>
