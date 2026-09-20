<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dx3ubrb9h"/><path class="hbtmd5b0k"/><path class="xgrnk0bjr"/><path class="m7m8cxbhm"/><path class="hl070ta8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:processing-record-outline-regular" /></template>
<style>
.dx3ubrb9h {
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.hbtmd5b0k {
  d: path("M9.5 7V2.5h5V7");
}

.hl070ta8t {
  d: path("M11 14h4");
}

.m7m8cxbhm {
  d: path("M11 11h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xgrnk0bjr {
  d: path("M9 10v7");
}

</style>
