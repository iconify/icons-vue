<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vapenum_d"/><path class="n8bikgk4k"/><path class="bnrswibpp"/><path class="yrlo_ib4h"/><path class="ets_btblg"/><path class="d5b4fcc2f"/><path class="vezho9b5g"/><path class="ul-6megvv"/><path class="hb39b-bug"/><path class="lqktbo2ou"/><path class="ejc7sbawl"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volume-anomaly-duotone-bold" /></template>
<style>
.bnrswibpp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d5b4fcc2f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ejc7sbawl {
  d: path("M20 15v4");
}

.ets_btblg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 15v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hb39b-bug {
  d: path("M12 3v16");
}

.lqktbo2ou {
  d: path("M16 12v7");
}

.n8bikgk4k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ul-6megvv {
  d: path("M8 11v8");
}

.vapenum_d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 14v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vezho9b5g {
  d: path("M4 14v5");
}

.yrlo_ib4h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
