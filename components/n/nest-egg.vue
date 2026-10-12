<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tab12-bgp"/><path class="i2vqtn8ma"/><path class="w27460--l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nest-egg" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2vqtn8ma {
  d: path("M5.75 16.5L12 18.25l6.25-1.75m-9.53-3.25A4.5 4.75 0 0 1 7.5 10c0-3.5 1.75-6.5 4.5-6.5s4.5 3 4.5 6.5a4.5 4.75 0 0 1-1.22 3.25Z");
}

.tab12-bgp {
  d: path("M2.75 13.25h18.5c0 4.5-4 8-9.25 8s-9.25-3.5-9.25-8");
}

.w27460--l {
  d: path("M13.13 8.02c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73");
}

</style>
