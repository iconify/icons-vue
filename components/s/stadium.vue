<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u65lzsd7g"/><path class="xboyprb7n"/><path class="mbcul6bgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stadium" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbcul6bgl {
  d: path("M6.75 9.5a5.25 2 0 0 1 10.5 0a5.25 2 0 0 1-10.5 0");
}

.u65lzsd7g {
  d: path("M2.75 9.5a9.25 4.75 0 0 1 18.5 0v6a9.25 4.75 0 0 1-18.5 0Z");
}

.xboyprb7n {
  d: path("M2.75 9.5a9.25 4.75 0 0 0 18.5 0M12 15.75v3M7 15v3m10-3v3");
}

</style>
