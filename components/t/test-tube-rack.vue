<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7yw9newa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-tube-rack" /></template>
<style>
.r7yw9newa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3v11.5a1.5 1.5 0 0 0 3 0V3m2.5 0v11.5a1.5 1.5 0 0 0 3 0V3M16 3v11.5a1.5 1.5 0 0 0 3 0V3M2.5 9h19m-19 10h19");
}

</style>
