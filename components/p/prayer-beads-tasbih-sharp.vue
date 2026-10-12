<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ki68xzb9g"/><circle class="bgbdgjb_a"/><path class="ttxmw6y7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prayer-beads-tasbih-sharp" /></template>
<style>
.bgbdgjb_a {
  cx: 12px;
  cy: 15.75px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ki68xzb9g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.47 14.6h.01m-2.19-3h.01m-.01-3.7h.01m2.17-3h.01M12 3.75h.01m3.52 1.15h.01m2.17 3h.01m-.01 3.7h.01m-2.19 3h.01");
}

.ttxmw6y7y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 17.25v1.25m0 0l-1.5 2.75M12 18.5l1.5 2.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
