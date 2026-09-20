<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4qft3b0u"/><path class="ewcibzbps"/><path class="qxhe48bjs"/><path class="ulbp0sbur"/><path class="hvp96bbhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:treehouse-duotone-thin" /></template>
<style>
.ewcibzbps {
  d: path("M5 14V9l7 -7 7 7v5Z");
}

.f4qft3b0u {
  fill: currentColor;
  d: path("M5 14V9l7 -7 7 7v5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvp96bbhp {
  d: path("m12 18 4 -4");
}

.qxhe48bjs {
  d: path("M12 14v7");
}

.ulbp0sbur {
  d: path("m12 18 -4 -4");
}

</style>
