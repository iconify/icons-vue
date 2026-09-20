<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jqwpjgbhg"/><path class="ztw87lr4b"/><path class="y0c1235en"/><path class="gy18-zqeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shell-duotone-thin" /></template>
<style>
.gy18-zqeb {
  d: path("M14 19h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqwpjgbhg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y0c1235en {
  d: path("m4 5 7 7 -7 7");
}

.ztw87lr4b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 19h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
