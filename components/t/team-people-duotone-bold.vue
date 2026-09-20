<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o0u5m7z1w"/><path class="y-n_bmb1w"/><path class="m_togmp4t"/><path class="j4jr16hcd"/><path class="xaz90clio"/><path class="g_eatebwd"/><path class="kx8w1xsla"/><path class="hf-3i5bym"/><path class="jnbv45bnp"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:team-people-duotone-bold" /></template>
<style>
.g_eatebwd {
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hf-3i5bym {
  d: path("M15 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.j4jr16hcd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 14a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jnbv45bnp {
  d: path("M14 14a3 3 0 0 1 6 0");
}

.kx8w1xsla {
  d: path("M4 14a3 3 0 0 1 6 0");
}

.m_togmp4t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 14a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o0u5m7z1w {
  fill: currentColor;
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xaz90clio {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y-n_bmb1w {
  fill: currentColor;
  d: path("M15 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
