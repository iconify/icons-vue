<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cirgusbhj"/><path class="ntc2gpbtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:power-restart" /></template>
<style>
.cirgusbhj {
  d: path("M17.142 6.872a8 8 0 1 1-10.284 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntc2gpbtp {
  d: path("M3.75 6.75h3v3M12 3v8");
}

</style>
