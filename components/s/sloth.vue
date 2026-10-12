<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="x-jp9cv2s"/><circle class="ny11racyo"/><path class="o8rc6zb1r"/><path class="fxtt7lqiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sloth" /></template>
<style>
.fxtt7lqiv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 13.75h.01m4.99 0h.01M12 17.25h.01");
}

.ny11racyo {
  cx: 12px;
  cy: 14px;
  r: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8rc6zb1r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 13.5c.5-1 1.75-1.5 2.75-1s1 1.75.25 2.5l-1 1c-.75.75-1.75.5-2.25-.25s-.25-1.5.25-2.25m8.5 0c-.5-1-1.75-1.5-2.75-1s-1 1.75-.25 2.5l1 1c.75.75 1.75.5 2.25-.25s.25-1.5-.25-2.25");
}

.x-jp9cv2s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4h18.5M6.75 9V5.5c0-1 .5-1.5 1.25-1.5m9.25 5V5.5c0-1-.5-1.5-1.25-1.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
