<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oibtokbpn"/><path class="yd1dd2b-v"/><path class="ueja73wqf"/><path class="wkf_8pb7a"/><path class="qrley9bmj"/><path class="ys-dg812g"/><path class="mjlof01ij"/><path class="ot1t9gb0r"/><path class="fevuzkbbx"/><path class="pubh6ib-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:percentile-rank-duotone-thin" /></template>
<style>
.fevuzkbbx {
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mjlof01ij {
  d: path("M6 14.5v3");
}

.oibtokbpn {
  fill: currentColor;
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ot1t9gb0r {
  d: path("M11 14.5v3");
}

.pubh6ib-w {
  d: path("M17 7v9");
}

.qrley9bmj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 7v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ueja73wqf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wkf_8pb7a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 14.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yd1dd2b-v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
