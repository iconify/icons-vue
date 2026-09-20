<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ga8_tozvo"/><path class="kb4ca79fq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:z-order-duotone-thin" /></template>
<style>
.ga8_tozvo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h16L6 19h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kb4ca79fq {
  d: path("M4 5h16L6 19h16");
}

</style>
