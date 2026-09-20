<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ibuanu9pl"/><path class="dl3j_ccmy"/><path class="ivhcn-dzy"/><path class="xtdc1ub4h"/><path class="xngyczooh"/><path class="c8b_wxbpu"/><path class="az1hpy9gr"/><path class="gl3o38_gx"/><path class="lzdsnnb7v"/><path class="q3srlnbfr"/><path class="dzjr38hwz"/><path class="s74j1ubnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-turbine-duotone-bold" /></template>
<style>
.az1hpy9gr {
  d: path("M12 9v12");
}

.c8b_wxbpu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m11 9 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dl3j_ccmy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dzjr38hwz {
  d: path("m13 9 5 5");
}

.gl3o38_gx {
  d: path("M8 21h8");
}

.ibuanu9pl {
  fill: currentColor;
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ivhcn-dzy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 21h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lzdsnnb7v {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.q3srlnbfr {
  d: path("M12 2v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s74j1ubnz {
  d: path("m11 9 -5 5");
}

.xngyczooh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 9 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xtdc1ub4h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
