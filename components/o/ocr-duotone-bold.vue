<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qckxdrbur"/><path class="kt3afhbmj"/><path class="bjiii8bpj"/><path class="q5pqb_bqs"/><path class="jmeghnglw"/><path class="b1_q35b2s"/><path class="dxxnlbcax"/><path class="a71lhwniq"/><path class="a-r3j5f7z"/><path class="xt7079b9x"/><path class="qvytntb8g"/><path class="s13ysjbyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ocr-duotone-bold" /></template>
<style>
.a-r3j5f7z {
  d: path("M3 16v4h5");
}

.a71lhwniq {
  d: path("M16 4h5v4");
}

.b1_q35b2s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 14h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bjiii8bpj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16v4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dxxnlbcax {
  d: path("M3 8V4h5");
}

.jmeghnglw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 10h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kt3afhbmj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 4h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q5pqb_bqs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 20h5v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qckxdrbur {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8V4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qvytntb8g {
  d: path("M7 10h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s13ysjbyf {
  d: path("M7 14h7");
}

.xt7079b9x {
  d: path("M16 20h5v-4");
}

</style>
