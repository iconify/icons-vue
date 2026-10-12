<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="f595v6brj"/><path class="kbttvrbvz"/><path class="dh4k9kbmu"/><rect class="nuad-hb6t"/><path class="r5hnywbfd"/><path class="c9qxs1b2r"/><path class="gnls4cc8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tls-handshake" /></template>
<style>
.c9qxs1b2r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 14.75h.01");
}

.dh4k9kbmu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 14.75h.01");
}

.f595v6brj {
  width: 6px;
  height: 9px;
  x: 2.75px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.gnls4cc8n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12.75h3.5M12.5 11.5l1.25 1.25L12.5 14m1.25 2.75h-3.5m1.25-1.25l-1.25 1.25L11.5 18");
}

.kbttvrbvz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 10.25V6.5a1.5 1.5 0 0 1 3 0v3.75");
}

.nuad-hb6t {
  width: 6px;
  height: 9px;
  x: 15.25px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.r5hnywbfd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 10.25V6.5a1.5 1.5 0 0 1 3 0v3.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
