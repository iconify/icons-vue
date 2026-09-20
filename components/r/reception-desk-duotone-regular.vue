<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w5o7xublt"/><path class="mm2blqb8p"/><path class="t7m3u2b0u"/><path class="c0_st1wwk"/><path class="zugrvnb7t"/><path class="a0e2epbbx"/><path class="ltriwmbuu"/><path class="us2evabuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reception-desk-duotone-regular" /></template>
<style>
.a0e2epbbx {
  d: path("M4 13v7h16v-7");
}

.c0_st1wwk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5.5V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ltriwmbuu {
  d: path("M8 10a4 4 0 0 1 8 0");
}

.mm2blqb8p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 13v7h16v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t7m3u2b0u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 10a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.us2evabuy {
  d: path("M12 5.5V8");
}

.w5o7xublt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
