<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="eqhi8eh4m"/><path class="juq33toqx"/><path class="r5ofaobrl"/><path class="qx2txqbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quiz-bulb" /></template>
<style>
.eqhi8eh4m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 17.25V15.9c0-1-.5-1.7-1.3-2.5a6 6 0 1 1 8.1 0c-.8.8-1.3 1.5-1.3 2.5v1.35Z");
}

.juq33toqx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.1 7.6a1.9 1.9 0 1 1 2.8 1.7c-.55.3-.9.75-.9 1.3v.6");
}

.qx2txqbrd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 20.75h4.5");
}

.r5ofaobrl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.4h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
