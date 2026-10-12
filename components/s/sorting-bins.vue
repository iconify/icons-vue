<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="r8r0sc-td"/><path class="qilery-5w"/><path class="yd1li5bra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sorting-bins" /></template>
<style>
.qilery-5w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.63 15h.01");
}

.r8r0sc-td {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.25H9.5q1 0 .94 1l-.63 10q-.06 1-1.06 1H4.5q-1 0-1.06-1l-.63-10q-.06-1 .94-1m10.75 0h5.75q1 0 .94 1l-.63 10q-.06 1-1.06 1h-4.25q-1 0-1.06-1l-.63-10q-.06-1 .94-1m-11.75-3h7.75m-5.25 0v-2.5H8v2.5m5.5 0h7.75m-5.25 0v-2.5h2.75v2.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yd1li5bra {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.62 13.69l1.14 2.12q.24.44-.26.44h-2.25q-.5 0-.26-.44l1.15-2.12q.24-.44.48 0");
}

</style>
