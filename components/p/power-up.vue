<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vhfy2kbyb"/><path class="wkrh57b9c"/><path class="suhhndjwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:power-up" /></template>
<style>
.suhhndjwd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 13.75h7.5v4.75A2.75 2.75 0 0 1 13 21.25h-2a2.75 2.75 0 0 1-2.75-2.75ZM10.5 16v1.75m3-1.75v1.75");
}

.vhfy2kbyb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.25a9 8.75 0 0 1 18 0a1.5 1.5 0 0 1-1.5 1.5h-15a1.5 1.5 0 0 1-1.5-1.5");
}

.wkrh57b9c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.5h.01m-4.26 2.75h.01m8.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
