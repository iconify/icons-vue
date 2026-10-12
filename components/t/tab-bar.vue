<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hufrlzpcu"/><path class="m9gn_vgpz"/><path class="qtyz7ml3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tab-bar" /></template>
<style>
.hufrlzpcu {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.m9gn_vgpz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14.75h17");
}

.qtyz7ml3f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 17.5h.01m4.49 0h.01m4.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
