<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oibtokbpn"/><path class="tbe304aqf"/><path class="yg2bvf0jn"/><path class="sg_-eykrh"/><path class="uyjdmcbzk"/><path class="ys-dg812g"/><path class="mjlof01ij"/><path class="ot1t9gb0r"/><path class="fevuzkbbx"/><path class="pubh6ib-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:percentile-rank-duotone-regular" /></template>
<style>
.fevuzkbbx {
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.mjlof01ij {
  d: path("M6 14.5v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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

.sg_-eykrh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 14.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tbe304aqf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uyjdmcbzk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 7v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yg2bvf0jn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 14.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
