<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="u7trvsbzf"/><path class="wb2vpv6rb"/><path class="b0ou8_8or"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ratchet-sharp" /></template>
<style>
.b0ou8_8or {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.3 7.05a7 7 0 1 1 0 9.9m1.75 0H9.3v1.75");
}

.u7trvsbzf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.65 10.5h-8.9v3h8.9a3 3 0 1 0 0-3Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wb2vpv6rb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 12h.01");
}

</style>
