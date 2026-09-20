<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ks3ax8u7u"/><path class="d1ogaqb9m"/><path class="pnk8nclld"/><path class="wcg-7deem"/><path class="oviel8bwg"/><path class="ou9p_ybmc"/><path class="k9n1nabge"/><path class="m45ql5bta"/><path class="s1n7yd_mp"/><path class="s92gxib6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:window-function-duotone-thin" /></template>
<style>
.d1ogaqb9m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9n1nabge {
  d: path("M3 10h12.5");
}

.ks3ax8u7u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m45ql5bta {
  d: path("M3 16h12.5");
}

.ou9p_ybmc {
  d: path("M3 4h12.5");
}

.oviel8bwg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 7H21v12h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pnk8nclld {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s1n7yd_mp {
  d: path("M3 22h12.5");
}

.s92gxib6y {
  d: path("M18.5 7H21v12h-2.5");
}

.wcg-7deem {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 22h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
