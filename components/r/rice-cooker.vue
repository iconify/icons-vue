<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="stpq14b-x"/><path class="vfxp3kw4q"/><path class="m9me6bb5j"/><rect class="e7vw-_3fk"/><path class="r9qy-z9uq"/><path class="zckadfbfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rice-cooker" /></template>
<style>
.e7vw-_3fk {
  width: 17.5px;
  height: 8.5px;
  x: 3.25px;
  y: 12.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.5px;
}

.m9me6bb5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01");
}

.r9qy-z9uq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 17H12");
}

.stpq14b-x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.83V4.5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v2.33");
}

.vfxp3kw4q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12.75a7.75 6.25 0 0 1 15.5 0Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zckadfbfg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 17h.01");
}

</style>
