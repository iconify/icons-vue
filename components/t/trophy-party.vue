<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="rdbnc-9_h"/><path class="ne_js1d8w"/><rect class="t280zus6r"/><path class="hh4tv2bea"/><path class="bdg-v1bjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trophy-party" /></template>
<style>
.bdg-v1bjo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.5 9.25h.01m16.99 0h.01");
}

.hh4tv2bea {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 3.5l1.5 1m16.5-1l-1.5 1M3 14.5l1.75-.75M21 14.5l-1.75-.75");
}

.ne_js1d8w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6H6.25a1.75 1.75 0 0 0 0 3.5H8M16 6h1.75a1.75 1.75 0 0 1 0 3.5H16m-4 3.25V17");
}

.rdbnc-9_h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 4h8v4.75a4 4 0 0 1-8 0Z");
}

.t280zus6r {
  width: 8px;
  height: 4.25px;
  x: 8px;
  y: 17px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
