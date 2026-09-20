<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="es4r-tbix"/><path class="berrgbclk"/><path class="eilmam0og"/><path class="gam3cw54g"/><path class="xgrfb-bqu"/><path class="qnmmmsbha"/><path class="klk7mdb2c"/><path class="h0co0sh-j"/><path class="ys-dg812g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tombstone-duotone-bold" /></template>
<style>
.berrgbclk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17.5 9.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eilmam0og {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20.5 9.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.es4r-tbix {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gam3cw54g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h0co0sh-j {
  d: path("m20.5 9.5 -3 3");
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.klk7mdb2c {
  d: path("m17.5 9.5 3 3");
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
