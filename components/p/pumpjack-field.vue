<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z1pzb2pdq"/><path class="dtrig44kf"/><path class="hxz4j4nld"/><path class="tm929zbzw"/><path class="n635hpbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pumpjack-field" /></template>
<style>
.dtrig44kf {
  fill: currentColor;
  d: path("M17.5 5c2.5 0 4.25 2.5 4.25 5.5h-2c0-1.5-.75-1.75-2.25-1.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxz4j4nld {
  d: path("m13.5 7l-3 14.5m3-14.5l3 14.5m4-11v7.75m0 0za1.25 1.25 0 0 1 1.25 1.25v.75a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-.75a1.25 1.25 0 0 1 1.25-1.25M2 13.5h4");
}

.n635hpbrq {
  d: path("m4 13.5l-1.25 8m1.25-8l1.25 8M2 21.5h20");
}

.tm929zbzw {
  fill: currentColor;
  d: path("M6 12.5c1.25 0 2 1 2 2.5H7c0-.75-.25-1.5-1-1.5Z");
}

.z1pzb2pdq {
  d: path("M10.5 7h7");
}

</style>
