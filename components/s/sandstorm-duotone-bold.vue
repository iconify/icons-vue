<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ppt4pgumd"/><path class="usaj3w3vt"/><path class="itzkgnr7u"/><path class="paf2fybga"/><path class="g91uwsb-i"/><path class="j3fr8pubv"/><path class="lmi4eb-oe"/><path class="igyz-cc5b"/><path class="zhhqt74pq"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sandstorm-duotone-bold" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.g91uwsb-i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.igyz-cc5b {
  d: path("M3 20a5 5 0 0 1 10 0");
}

.itzkgnr7u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j3fr8pubv {
  d: path("M3 6h15");
}

.lmi4eb-oe {
  d: path("M5 10h16");
}

.paf2fybga {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 20a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ppt4pgumd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.usaj3w3vt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 10h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zhhqt74pq {
  d: path("M13 20a4 4 0 0 1 8 0");
}

</style>
