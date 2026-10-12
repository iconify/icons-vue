<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hy7sghflf"/><path class="hvcrdn6wo"/><path class="i-09z4cpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mole-sharp" /></template>
<style>
.hvcrdn6wo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 16.4l-1 3.85h3.25l.5-3.25M13 17l-.5 3.25H16l.25-3.25");
}

.hy7sghflf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 12.5L8.5 9.25C10 8 11.75 7.5 13.5 7.5c4.25 0 7.5 2.75 7.5 6c0 2-1.5 3.5-3.5 3.5H7.75l-1.5-1.5l-3-1.75l-.942-.625z");
}

.i-09z4cpn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 11h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
