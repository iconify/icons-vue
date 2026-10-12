<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="v8ysr6bgj"/><path class="ff151fxpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:taxi-stand-sign-sharp" /></template>
<style>
.ff151fxpk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 13.75h.01m5.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v8ysr6bgj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16v-3.25l1.5-3.5h7l1.5 3.5V16Zm1 0v1.75M16 16v1.75m-5.5-11h3");
}

.ywno-sh7h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
