<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ajc_0cc0i"/><path class="j3-l_7bcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shale-layer" /></template>
<style>
.ajc_0cc0i {
  d: path("M5.75 4.5h14a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-14A1.75 1.75 0 0 1 4 7.75v-1.5A1.75 1.75 0 0 1 5.75 4.5m-1.5 5h13.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 4.25 9.5m1 5h14.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-1.5a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3-l_7bcj {
  d: path("m12.25 7l.949 1.898a1.5 1.5 0 0 1 .051 1.227l-1.527 3.818a1.5 1.5 0 0 0 0 1.114L12.5 17a.291.291 0 0 0 .557-.156L11.46 7.257A.42.42 0 0 1 12.25 7");
}

</style>
