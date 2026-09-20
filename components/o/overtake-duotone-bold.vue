<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t830b32gy"/><path class="x-7dxbcyu"/><path class="ln_5yacac"/><path class="hhwp_ccfq"/><path class="ddx1lo_hx"/><path class="nbr7qebnn"/><path class="hcn-wubvk"/><path class="toy0nxbdm"/><path class="ler50rfbf"/><path class="caiwqabfd"/><path class="qw9zcf0wd"/><path class="beunabbsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:overtake-duotone-bold" /></template>
<style>
.beunabbsv {
  d: path("M12.5 6.5 15 4l2.5 2.5");
}

.caiwqabfd {
  d: path("M6.5 10.5 9 8l2.5 2.5");
}

.ddx1lo_hx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hcn-wubvk {
  d: path("M3 2v20");
}

.hhwp_ccfq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6.5 10.5 9 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ler50rfbf {
  d: path("M9 8v12");
}

.ln_5yacac {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nbr7qebnn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.5 6.5 15 4l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qw9zcf0wd {
  d: path("M15 4v12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t830b32gy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.toy0nxbdm {
  d: path("M21 2v20");
}

.x-7dxbcyu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
