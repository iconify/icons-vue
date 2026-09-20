<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lu8t8bbdh"/><path class="py2gs-b2y"/><path class="k-pazuz_e"/><path class="b8jy_fqhz"/><path class="k187sabpz"/><path class="yaok4e85l"/><path class="pdgwdvrql"/><path class="o0r0bcbwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:uptime-duotone-thin" /></template>
<style>
.b8jy_fqhz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 6 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-pazuz_e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k187sabpz {
  d: path("M2 11h20");
}

.lu8t8bbdh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 11h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o0r0bcbwx {
  d: path("m16 6 2 2 4 -4");
}

.pdgwdvrql {
  d: path("M15 17h7");
}

.py2gs-b2y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 17h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yaok4e85l {
  d: path("M2 17h9");
}

</style>
