<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zb3ih3b5m"/><path class="snp9g4ldm"/><path class="v7o_hzbwh"/><path class="oz3eccbug"/><path class="ls_1jlbjr"/><path class="mhf9v2bnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scarf-duotone-bold" /></template>
<style>
.ls_1jlbjr {
  d: path("M7 8v10h4V8");
}

.mhf9v2bnf {
  d: path("M14 11v10h4V11");
}

.oz3eccbug {
  d: path("M7 8a5 5 0 0 1 10 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.snp9g4ldm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8v10h4V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v7o_hzbwh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 11v10h4V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zb3ih3b5m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
