<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vnrxpx35b"/><path class="d4w2c-elu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:package-return" /></template>
<style>
.d4w2c-elu {
  d: path("M9 10.25v3m11.5 2v-7.5a2.5 2.5 0 0 0-2.5-2.5h-7.5M12.75 3L10.5 5.25l2.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vnrxpx35b {
  width: 12.5px;
  height: 11px;
  x: 2.75px;
  y: 10.25px;
  rx: 1.5px;
}

</style>
