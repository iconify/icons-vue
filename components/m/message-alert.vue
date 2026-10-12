<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><path class="f-wqggb9w"/><path class="maf5by7ww"/></g><path class="yr-noebov"/><path class="fxu54sbac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:message-alert" /></template>
<style>
.f-wqggb9w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25c4.85 0 8.75 3.5 8.75 7.85s-3.9 7.85-8.75 7.85c-1.1 0-2.15-.18-3.1-.5L4.6 20c-.6.2-1.15-.4-.9-.95l1.2-2.9c-1-1.4-1.65-3.15-1.65-5.05c0-4.35 3.9-7.85 8.75-7.85");
}

.fxu54sbac {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 20.25h.01");
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.maf5by7ww {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11.1h.01m3.99 0h.01m3.99 0h.01");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yr-noebov {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 14.5v3.25");
}

</style>
