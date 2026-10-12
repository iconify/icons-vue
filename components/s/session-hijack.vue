<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="rbky1obji"/><path class="x1jo36kgt"/><path class="bu0-k5zcw"/><path class="lfp0opz-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:session-hijack" /></template>
<style>
.bu0-k5zcw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.18 12.06a4.75 4.75 0 1 0 2.76 2.76a2 2 0 0 1-2.76-2.76");
}

.lfp0opz-t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 15.75h.01M17.5 18h.01");
}

.rbky1obji {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.75 9.08V5.25a2 2 0 0 0-2-2h-12a2 2 0 0 0-2 2v8.5a2 2 0 0 0 2 2h4.04m-6.04-8h16");
}

.x1jo36kgt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 5.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
