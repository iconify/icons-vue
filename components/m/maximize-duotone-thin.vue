<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_rniwbjv"/><path class="l7hrykbmz"/><path class="xnjbm9uky"/><path class="xqpej4bek"/><path class="l6e2wzbuh"/><path class="qtj-xccdg"/><path class="ne_b8wtyo"/><path class="fsv7g_bbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:maximize-duotone-thin" /></template>
<style>
.fsv7g_bbj {
  d: path("M9 21H3v-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6e2wzbuh {
  d: path("M3 9V3h6");
}

.l7hrykbmz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 3h6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ne_b8wtyo {
  d: path("M21 15v6h-6");
}

.q_rniwbjv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9V3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qtj-xccdg {
  d: path("M15 3h6v6");
}

.xnjbm9uky {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 15v6h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xqpej4bek {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 21H3v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
