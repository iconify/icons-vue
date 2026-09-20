<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gsvssdbyc"/><path class="v9yujbbpa"/><path class="lwcjgibmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tea-ceremony-outline-thin" /></template>
<style>
.gsvssdbyc {
  d: path("M5 12h12v4c0 3 -3 4 -6 4s-6 -1 -6 -4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwcjgibmo {
  d: path("M7 12c0 -3 2 -5 4 -5s4 2 4 5");
}

.v9yujbbpa {
  d: path("m17 14 3 -3");
}

</style>
