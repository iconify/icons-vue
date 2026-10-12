<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z77_krbbr"/><path class="ts1wndbaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prayer-mat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ts1wndbaa {
  d: path("M7.5 2.75v1.5m3-1.5v1.5m3-1.5v1.5m3-1.5v1.5m-9 15.5v1.5m3-1.5v1.5m3-1.5v1.5m3-1.5v1.5m-8-4.5V11a3.5 3.5 0 0 1 7 0v5.75");
}

.z77_krbbr {
  width: 14px;
  height: 15.5px;
  x: 5px;
  y: 4.25px;
  rx: 1.5px;
}

</style>
