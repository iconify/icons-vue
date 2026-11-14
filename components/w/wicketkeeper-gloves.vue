<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo0qo13hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wicketkeeper-gloves" /></template>
<style>
.xo0qo13hk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 18v-3l-3-3A1.75 1.75 0 0 1 7 9.5l.5.5V5.75a1.75 1.75 0 0 1 3.5 0V4.5a1.75 1.75 0 0 1 3.5 0v1.25a1.75 1.75 0 0 1 3.5 0V18m-9.75 0h9A1.75 1.75 0 0 1 19 19.75a1.75 1.75 0 0 1-1.75 1.75h-9a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 8.25 18M11 5.75V11m3.5-5.25V11");
}

</style>
