<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xodoppbub"/><path class="r-_xorlci"/><path class="ixx7a8jxa"/><path class="sooj-ebve"/><path class="hgb637bhu"/><path class="x2rmxpb0x"/><path class="bv72su-ri"/><path class="autc-bc3p"/><path class="bvirm9d4j"/><path class="a2pxmcc-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reranker-duotone-thin" /></template>
<style>
.a2pxmcc-f {
  d: path("m18 16 2 2 2 -2");
}

.autc-bc3p {
  d: path("M3 18h13");
}

.bv72su-ri {
  d: path("M3 12h13");
}

.bvirm9d4j {
  d: path("M20 6v12");
}

.hgb637bhu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 16 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixx7a8jxa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r-_xorlci {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sooj-ebve {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x2rmxpb0x {
  d: path("M3 6h13");
}

.xodoppbub {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
