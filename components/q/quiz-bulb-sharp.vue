<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="o942btzjj"/><path class="zc38n4apu"/><path class="r5ofaobrl"/><path class="qx2txqbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quiz-bulb-sharp" /></template>
<style>
.o942btzjj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 17.25V14.7l-1.3-1.3a6 6 0 1 1 8.1 0l-1.3 1.3v2.55Z");
}

.qx2txqbrd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 20.75h4.5");
}

.r5ofaobrl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.4h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zc38n4apu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.1 7.6a1.9 1.9 0 1 1 2.8 1.7l-.9.491V11.2");
}

</style>
