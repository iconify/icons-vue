<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fqapklbmg"/><path class="eyyyeghth"/><path class="r182r524c"/><path class="r_4k1sbsg"/><path class="zwgz_-bzc"/><path class="ivxatgkif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mock-exam-duotone-bold" /></template>
<style>
.eyyyeghth {
  d: path("M4 3h16v18H4Z");
}

.fqapklbmg {
  fill: currentColor;
  d: path("M4 3h16v18H4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ivxatgkif {
  d: path("m19 15 -6 6");
}

.r_4k1sbsg {
  d: path("M7 13h6");
}

.r182r524c {
  d: path("M7 9h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zwgz_-bzc {
  d: path("m13 15 6 6");
}

</style>
