<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x2r2iccmd"/><circle class="xej0afb8f"/><path class="fv1wuac9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oil-lamp-sacred" /></template>
<style>
.fv1wuac9w {
  d: path("M7.5 21.25c0-1.5 2-2.5 4.5-2.5s4.5 1 4.5 2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2r2iccmd {
  d: path("M7.5 3.25C8.4 4.35 9 5.15 9 6a1.5 1.5 0 0 1-3 0c0-.85.6-1.65 1.5-2.75m4.5 0c.9 1.1 1.5 1.9 1.5 2.75a1.5 1.5 0 0 1-3 0c0-.85.6-1.65 1.5-2.75m4.5 0C17.4 4.35 18 5.15 18 6a1.5 1.5 0 0 1-3 0c0-.85.6-1.65 1.5-2.75m-12 6h15a7.5 3 0 0 1-15 0m7.5 3V14m0 3v1.75");
}

.xej0afb8f {
  cx: 12px;
  cy: 15.5px;
  r: 1.5px;
}

</style>
