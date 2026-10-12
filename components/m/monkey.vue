<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z8shabbus"/><path class="qvihplcjl"/><path class="lcdu-hbje"/><path class="y-zpp35rt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monkey" /></template>
<style>
.lcdu-hbje {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10.75h.01m3.99 0h.01");
}

.qvihplcjl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25c-.5-.5-1.25-.75-2-.75c-1.25 0-2.25 1-2.25 2.25c0 .6.2 1.1.5 1.5c-.35.45-.5 1-.5 1.5c0 1.75 1.9 3 4.25 3s4.25-1.25 4.25-3c0-.5-.15-1.05-.5-1.5c.3-.4.5-.9.5-1.5c0-1.25-1-2.25-2.25-2.25c-.75 0-1.5.25-2 .75");
}

.y-zpp35rt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14.25c.9.6 2.1.6 3 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z8shabbus {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.37 14.75a2.5 2.5 0 1 1 .18-4.98a7 7 0 0 1 12.9 0a2.5 2.5 0 1 1 .18 4.98a7 7 0 0 1-13.26 0");
}

</style>
