<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="de23ghs-u"/><path class="p-3tqnbzb"/><path class="qrqlpabxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plaster-outline-thin" /></template>
<style>
.de23ghs-u {
  d: path("m3.5 15.5 12 -12a4 4 0 0 1 5 5l-12 12a4 4 0 0 1 -5 -5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p-3tqnbzb {
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qrqlpabxp {
  d: path("M13 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
