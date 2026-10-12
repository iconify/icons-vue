<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wpkxcinkv"/><path class="ipqtv491q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-quality" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipqtv491q {
  d: path("m9.01 12.57l2.98 1.86q.51.32 0 .64l-2.98 1.86q-.51.32-.51-.28v-3.8q0-.6.51-.28M18.5 3q.3 2.2 2.5 2.5q-2.2.3-2.5 2.5q-.3-2.2-2.5-2.5q2.2-.3 2.5-2.5");
}

.wpkxcinkv {
  width: 14.5px;
  height: 11px;
  x: 2.75px;
  y: 9.25px;
  rx: 2.5px;
}

</style>
