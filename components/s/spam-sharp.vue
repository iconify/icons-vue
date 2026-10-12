<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pevf0rbvb"/><path class="uk0i7lbye"/><circle class="ffz4idt6b"/><path class="u7uwe924o"/><path class="f391oyb0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spam-sharp" /></template>
<style>
.f391oyb0h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 9h.01");
}

.ffz4idt6b {
  cx: 17.25px;
  cy: 6.75px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pevf0rbvb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25h14v8h-14z");
}

.u7uwe924o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 4.75V7");
}

.uk0i7lbye {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.25 15.5l3.15 2l1.35 1.013L11.1 17.5l3.15-2");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
