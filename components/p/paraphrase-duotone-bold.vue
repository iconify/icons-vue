<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="h2sq3fbpa"/><path class="j5fopqp8s"/><path class="f74e98i-u"/><path class="wn9wk7b3u"/><path class="eslycc4vy"/><path class="xgrfb-bqu"/><path class="xyj-l9cjp"/><path class="f26bn-hui"/><path class="l8vl6rdup"/><path class="dti01qb8s"/><path class="l76jezbpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:paraphrase-duotone-bold" /></template>
<style>
.dti01qb8s {
  d: path("M16 9v6");
}

.eslycc4vy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 11.5 16 9l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f26bn-hui {
  d: path("M8 9v6");
}

.f74e98i-u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 12.5 8 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2sq3fbpa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j5fopqp8s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l76jezbpv {
  d: path("M13.5 11.5 16 9l2.5 2.5");
}

.l8vl6rdup {
  d: path("M5.5 12.5 8 15l2.5 -2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wn9wk7b3u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
