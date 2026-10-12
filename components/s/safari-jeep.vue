<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z19myum2h"/><circle class="r0ew8gbrg"/><path class="fnrnvwv4f"/><circle class="riohgnbtm"/><path class="g27ahybtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safari-jeep" /></template>
<style>
.fnrnvwv4f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 19h.01");
}

.g27ahybtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 19h.01");
}

.r0ew8gbrg {
  cx: 9.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.riohgnbtm {
  cx: 17.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z19myum2h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11V9a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v2m-8.75 4.75V12q0-1 1-1h7.75q1 0 1.71.71l.08.08q.71.71 1.71.71h2.25q1 0 1 1v2.25q0 1-1 1H6.75q-1 0-1-1");
}

</style>
