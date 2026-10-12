<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cjg_b0bqy"/><circle class="rzqvhrb3a"/><path class="dwnhvlaym"/><circle class="z1jlxibqc"/><path class="fb03m042k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roller-skate" /></template>
<style>
.cjg_b0bqy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 4.25a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1V8l4.5 1.5a4 4 0 0 1 2.5 3.25v.5a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1Zm2.25 2h2");
}

.dwnhvlaym {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 19h.01");
}

.fb03m042k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 19h.01");
}

.rzqvhrb3a {
  cx: 8px;
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

.z1jlxibqc {
  cx: 16.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
