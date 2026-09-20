<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l46grxbhs"/><path class="zqkak5jxl"/><path class="s_smhub4e"/><path class="d4rfzbb0c"/><path class="bx_argeyt"/><path class="upu8uhb6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:user-consent-duotone-thin" /></template>
<style>
.bx_argeyt {
  d: path("M4 15a4 4 0 0 1 8 0");
}

.d4rfzbb0c {
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l46grxbhs {
  fill: currentColor;
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s_smhub4e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 13 2 2 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.upu8uhb6u {
  d: path("m14 13 2 2 3.5 -3.5");
}

.zqkak5jxl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 15a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
