<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lcfyq8tea"/><rect class="l_8m8bc5a"/><circle class="t18z8vfkj"/><path class="y4fu0_bxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:travel-adapter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_8m8bc5a {
  width: 15.5px;
  height: 13.5px;
  x: 4.25px;
  y: 7.75px;
  rx: 2.5px;
}

.lcfyq8tea {
  d: path("M9 7.75V3m6 4.75V3");
}

.t18z8vfkj {
  cx: 12px;
  cy: 14.5px;
  r: 4px;
}

.y4fu0_bxm {
  d: path("M10.5 13.5v2m3-2v2");
}

</style>
