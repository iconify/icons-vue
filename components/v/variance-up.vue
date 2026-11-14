<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="psfeu5kvd"/><path class="b5uyvnbwq"/><path class="ujof44wqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:variance-up" /></template>
<style>
.b5uyvnbwq {
  fill: currentColor;
  d: path("M15 7h2.5A1.5 1.5 0 0 1 19 8.5V20a1.5 1.5 0 0 1-1.5 1.5H15a1.5 1.5 0 0 1-1.5-1.5V8.5A1.5 1.5 0 0 1 15 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.psfeu5kvd {
  d: path("M6 11h2.5a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20v-7.5A1.5 1.5 0 0 1 6 11");
}

.ujof44wqh {
  d: path("M2.5 21.5h19M11.5 11h.75m8 0h1.25m-5.25-5.75v-3M14.5 4l1.75-1.75L18 4");
}

</style>
