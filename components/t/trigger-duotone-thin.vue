<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l6esejb_g"/><path class="pdu-xkbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6esejb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 4 -7 7h5l-7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pdu-xkbsu {
  d: path("m16 4 -7 7h5l-7 7");
}

</style>
