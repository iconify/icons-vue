<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvee-xzfj"/><path class="rqjbofjex"/><path class="akcvysb4c"/><path class="jh6waltkl"/><path class="t-ht_no5g"/><path class="gcalxb98a"/><path class="ckrzk6zny"/><path class="qtxvlht3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prescription-refill-duotone-thin" /></template>
<style>
.akcvysb4c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 10.5 8 13l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ckrzk6zny {
  d: path("M10.5 10.5 8 13l2.5 2.5");
}

.gcalxb98a {
  d: path("M8 13h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jh6waltkl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qtxvlht3c {
  d: path("M8 17h8");
}

.rqjbofjex {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 13h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t-ht_no5g {
  d: path("M4 3h14l4 4v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V5a2 2 0 0 1 2 -2m14 0v4h4");
}

.tvee-xzfj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3h14l4 4v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V5a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
