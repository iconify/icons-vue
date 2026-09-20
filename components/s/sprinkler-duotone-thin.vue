<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tbr--mb3k"/><path class="b6wmnjuyp"/><path class="fh6u24prw"/><path class="ftpoa0bjf"/><path class="aun8ln3zw"/><path class="xedmbxbzm"/><path class="t6kwsvo7n"/><path class="pg19afyuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sprinkler-duotone-thin" /></template>
<style>
.aun8ln3zw {
  d: path("M12 12v7");
}

.b6wmnjuyp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fh6u24prw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 8c2 -2 4 -2 6 -1");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ftpoa0bjf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8C7 6 5 6 3 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pg19afyuh {
  d: path("M9 8C7 6 5 6 3 7");
}

.t6kwsvo7n {
  d: path("M15 8c2 -2 4 -2 6 -1");
}

.tbr--mb3k {
  fill: currentColor;
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xedmbxbzm {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
