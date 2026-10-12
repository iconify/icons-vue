<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wcklgubij"/><path class="jrfnoyaqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:police-station" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jrfnoyaqa {
  d: path("m12 10.25l3.25 1.25V14c0 2.1-1.35 3.65-3.25 4.5c-1.9-.85-3.25-2.4-3.25-4.5v-2.5Z");
}

.wcklgubij {
  d: path("m4.27 8.52l6.71-4.79q1.02-.73 2.04 0l6.71 4.79q1.02.73 1.02 1.98V20q0 1.25-1.25 1.25h-15q-1.25 0-1.25-1.25v-9.5q0-1.25 1.02-1.98");
}

</style>
