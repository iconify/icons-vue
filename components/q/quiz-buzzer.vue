<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f1kba36vl"/><path class="lu8a-i6tb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:quiz-buzzer" /></template>
<style>
.f1kba36vl {
  d: path("M2.5 16h19v4.5h-19ZM5 16a7 7 0 0 1 14 0");
}

.lu8a-i6tb {
  d: path("M10 9.25V5.5h4v3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
