<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l342qj1rt"/><path class="j8b-5dbak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:usb-c" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8b-5dbak {
  d: path("M8.5 10.5h7A1.5 1.5 0 0 1 17 12a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 12a1.5 1.5 0 0 1 1.5-1.5");
}

.l342qj1rt {
  d: path("M7.75 6.5h8.5a5.25 5.25 0 0 1 5.25 5.25v.5a5.25 5.25 0 0 1-5.25 5.25h-8.5a5.25 5.25 0 0 1-5.25-5.25v-.5A5.25 5.25 0 0 1 7.75 6.5");
}

</style>
