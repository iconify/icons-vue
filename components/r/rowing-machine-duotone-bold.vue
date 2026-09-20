<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jdh2e3b6a"/><path class="ht9zq9bpv"/><path class="g_i5rf1-x"/><path class="au8_9lgpz"/><path class="scmlkubbj"/><path class="yngda3bvc"/><path class="x1_r36phd"/><path class="rrzohjbez"/><path class="gstzuxb9r"/><path class="wggowmhtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rowing-machine-duotone-bold" /></template>
<style>
.au8_9lgpz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g_i5rf1-x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gstzuxb9r {
  d: path("M5 7v4");
}

.ht9zq9bpv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jdh2e3b6a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 15h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rrzohjbez {
  d: path("M12 12v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.scmlkubbj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 9h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wggowmhtc {
  d: path("M5 9h4");
}

.x1_r36phd {
  d: path("M9 12h6");
}

.yngda3bvc {
  d: path("M3 15h18");
}

</style>
