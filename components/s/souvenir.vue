<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="iejqtrbgm"/><path class="qf_lp-5rx"/><path class="tx-15vb7y"/><path class="x3ze-d0du"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:souvenir" /></template>
<style>
.iejqtrbgm {
  cx: 12px;
  cy: 9.75px;
  r: 7px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qf_lp-5rx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.31 6.93l2.38 5.14q.31.68-.44.68h-4.5q-.75 0-.44-.68l2.38-5.14q.31-.68.62 0");
}

.tx-15vb7y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 8.5h.01M16 7.25h.01m.74 2.5h.01");
}

.x3ze-d0du {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 16.75h8.5q1 0 1.36.93l1.03 2.64q.36.93-.64.93H6q-1 0-.64-.93l1.03-2.64q.36-.93 1.36-.93");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
