<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ly92b117j"/><circle class="n3ftt6b_u"/><circle class="pa25adc6f"/><circle class="tgk-geb5y"/><circle class="y7zsl24ft"/><circle class="nzgvifbys"/><circle class="hox7_vocr"/><circle class="pjcuitb1a"/><circle class="fd52k9cob"/><circle class="pjzu56bly"/><path class="ixm-1o03z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prayer-beads" /></template>
<style>
.fd52k9cob {
  cx: 17px;
  cy: 13.74px;
  r: 0.375px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hox7_vocr {
  cx: 19.24px;
  cy: 6.8px;
  r: 0.375px;
}

.ixm-1o03z {
  d: path("M12 18.5v2m-1.5.75l1.5-1l1.5 1");
}

.ly92b117j {
  cx: 6.98px;
  cy: 13.73px;
  r: 0.375px;
}

.n3ftt6b_u {
  cx: 4.27px;
  cy: 10.73px;
  r: 0.375px;
}

.nzgvifbys {
  cx: 16.05px;
  cy: 4.29px;
  r: 0.375px;
}

.pa25adc6f {
  cx: 4.77px;
  cy: 6.79px;
  r: 0.375px;
}

.pjcuitb1a {
  cx: 19.72px;
  cy: 10.75px;
  r: 0.375px;
}

.pjzu56bly {
  cx: 12px;
  cy: 17px;
  r: 1.5px;
}

.tgk-geb5y {
  cx: 7.97px;
  cy: 4.28px;
  r: 0.375px;
}

.y7zsl24ft {
  cx: 12px;
  cy: 3.5px;
  r: 0.375px;
}

</style>
