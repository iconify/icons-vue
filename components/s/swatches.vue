<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="fxazmktkk"/><path class="bd9gzlbmu"/><path class="zhbbeubgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swatches" /></template>
<style>
.bd9gzlbmu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 17.5h.01");
}

.fxazmktkk {
  width: 6.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zhbbeubgv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.55 6.5l3.15-1.82q1.3-.75 2.05.55l1.75 3.03q.75 1.3-.55 2.05l-6.4 3.7q-1.3.75-1.3-.75V8.75q0-1.5 1.3-2.25m-1.3 9.75h10a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-10Z");
}

</style>
