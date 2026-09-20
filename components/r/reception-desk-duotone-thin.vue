<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_hy4hbgg"/><path class="xdpo42bfg"/><path class="yeegcybnz"/><path class="bpah47shs"/><path class="zugrvnb7t"/><path class="a0e2epbbx"/><path class="ltriwmbuu"/><path class="us2evabuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reception-desk-duotone-thin" /></template>
<style>
.a0e2epbbx {
  d: path("M4 13v7h16v-7");
}

.bpah47shs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5.5V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f_hy4hbgg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ltriwmbuu {
  d: path("M8 10a4 4 0 0 1 8 0");
}

.us2evabuy {
  d: path("M12 5.5V8");
}

.xdpo42bfg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 13v7h16v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yeegcybnz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 10a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
