<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_h_wizsz"/><path class="u8zx72yhd"/><path class="phvinrjsl"/><path class="uykap1ufa"/><path class="vzegeabik"/><path class="bta3msbel"/><path class="w-0ktubui"/><path class="yxcg20bta"/><path class="c0_odobsd"/><path class="gvfa1mb1f"/><path class="qhy91zm_e"/><path class="okzo6wb9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ocr-ingest-duotone-thin" /></template>
<style>
.bta3msbel {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c0_odobsd {
  d: path("M3 17v3h3");
}

.gvfa1mb1f {
  d: path("M11 20h3v-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_h_wizsz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7V4h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.okzo6wb9p {
  d: path("m17 10 2 2 -2 2");
}

.phvinrjsl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17v3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qhy91zm_e {
  d: path("M6 12h5");
}

.u8zx72yhd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 4h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uykap1ufa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 20h3v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vzegeabik {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w-0ktubui {
  d: path("M3 7V4h3");
}

.yxcg20bta {
  d: path("M11 4h3v3");
}

</style>
