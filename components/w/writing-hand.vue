<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="to6r2abfp"/><path class="wy0x8llmy"/><path class="sgyxn-zbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:writing-hand" /></template>
<style>
.sgyxn-zbj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 20H21");
}

.to6r2abfp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.55 11.3l1.15-1.85q1.05-1.7 3.05-1.7H16q2 0 3.41 1.41l.43.43Q21.25 11 21.25 13v2.25q0 2-2 2H15.5q-2 0-3.37-1.46l-1.26-1.33Q9.5 13 10.55 11.3m4.95-.55h3.25m-3.5 2.75h3.5m-.09-10.1L16 7.75m-4.5 7.35l-1.3 2.13");
}

.wy0x8llmy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 20h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
