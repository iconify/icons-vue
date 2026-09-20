<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f2s0o7o5j"/><path class="f59axuhhu"/><path class="ldfbmybql"/><path class="pcl5pkbcw"/><path class="votyijv0m"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sky-clear-outline-thin" /></template>
<style>
.f2s0o7o5j {
  d: path("M7.5 9a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.f59axuhhu {
  d: path("M4.5 4.5 7 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldfbmybql {
  d: path("M19.5 4.5 17 7");
}

.pcl5pkbcw {
  d: path("M2 9h3");
}

.votyijv0m {
  d: path("M19 9h3");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
