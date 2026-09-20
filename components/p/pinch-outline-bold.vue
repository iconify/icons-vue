<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fpxzcl19b"/><path class="m3uk2nwvd"/><path class="v8mti3bcl"/><path class="m_x-fjbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pinch-outline-bold" /></template>
<style>
.fpxzcl19b {
  d: path("m3 3 6 6");
}

.m_x-fjbot {
  d: path("M15 18.5V15h3.5");
}

.m3uk2nwvd {
  d: path("M9 5.5V9H5.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v8mti3bcl {
  d: path("m21 21 -6 -6");
}

</style>
