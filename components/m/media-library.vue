<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jyzbpctkd"/><rect class="wox5_pmda"/><path class="xjbm2mbab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:media-library" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jyzbpctkd {
  d: path("M4.25 3.75v16.5m4-16.5v16.5");
}

.wox5_pmda {
  width: 10px;
  height: 13px;
  x: 11.25px;
  y: 7.25px;
  rx: 2.5px;
}

.xjbm2mbab {
  d: path("m15.33 11.64l2.59 1.72q.58.39 0 .78l-2.59 1.72q-.58.39-.58-.31v-3.6q0-.7.58-.31");
}

</style>
