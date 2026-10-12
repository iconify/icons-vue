<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="prhyas63w"/><circle class="xjynbecfo"/><path class="ts9eagb1i"/><circle class="zkqnmjbsk"/><path class="njenmdbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timing-belt" /></template>
<style>
.njenmdbpf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 12h.01");
}

.prhyas63w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 6.5h7.5a5.5 5.5 0 0 1 0 11h-7.5a5.5 5.5 0 0 1 0-11");
}

.ts9eagb1i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 12h.01");
}

.xjynbecfo {
  cx: 8.25px;
  cy: 12px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zkqnmjbsk {
  cx: 15.75px;
  cy: 12px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
