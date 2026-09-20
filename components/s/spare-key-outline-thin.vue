<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aj1uncbqw"/><path class="uuhe-zb-s"/><path class="j4po9lbmx"/><path class="oo-1hhwik"/><path class="mb3fb7bkl"/><path class="hepg2-exf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spare-key-outline-thin" /></template>
<style>
.aj1uncbqw {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.hepg2-exf {
  d: path("M14 16h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4po9lbmx {
  d: path("M7 16h3");
}

.mb3fb7bkl {
  d: path("M17 10v10");
}

.oo-1hhwik {
  d: path("M14 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.uuhe-zb-s {
  d: path("M7 10v10");
}

</style>
