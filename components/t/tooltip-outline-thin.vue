<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wmpj7cbtn"/><path class="r182r524c"/><path class="ephqv81ta"/><path class="bgd-y5boh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tooltip-outline-thin" /></template>
<style>
.bgd-y5boh {
  d: path("M11 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ephqv81ta {
  d: path("m9.5 14 2.5 2.5 2.5 -2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r182r524c {
  d: path("M7 9h10");
}

.wmpj7cbtn {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
