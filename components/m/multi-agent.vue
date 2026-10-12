<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="vr39umbhr"/><rect class="yb4u4tcfy"/><path class="vfnk_yb5j"/><path class="xbkud52my"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:multi-agent" /></template>
<style>
.vfnk_yb5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 14.5h.01m2.99 0h.01m7.49 0h.01m2.99 0h.01");
}

.vr39umbhr {
  width: 8px;
  height: 9px;
  x: 2.75px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.xbkud52my {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.25 7.5l-2 2.75m5.5-2.75l2 2.75M12 2.75q.3 2.2 2.5 2.5q-2.2.3-2.5 2.5q-.3-2.2-2.5-2.5q2.2-.3 2.5-2.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yb4u4tcfy {
  width: 8px;
  height: 9px;
  x: 13.25px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

</style>
