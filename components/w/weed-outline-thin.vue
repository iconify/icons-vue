<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rrwm8uaph"/><path class="j2d9j4b0r"/><path class="miurf-h0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weed-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2d9j4b0r {
  d: path("M12 12 8 8h4L8 4");
}

.miurf-h0g {
  d: path("M5 18h14");
}

.rrwm8uaph {
  d: path("M12 4v14");
}

</style>
