<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o8avw27mx"/><path class="nhfwqhnos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:motion-zone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhfwqhnos {
  d: path("m8.5 12.5l2-1.75h2L14 12.5l2 .5");
}

.o8avw27mx {
  d: path("M2.5 7V2.5H7m10 0h4.5V7m0 10v4.5H17m-10 0H2.5V17m8.75-10.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m1.25 4.5l-1 3.25l1.75 2l.5 3m-2.25-5L10 16.5l-1.75 1");
}

</style>
