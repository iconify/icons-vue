<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cjlz_nyrn"/><path class="ink232jbr"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mileage-claim" /></template>
<style>
.cjlz_nyrn {
  d: path("M15.26 12.5H3v-3q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4.5 8H6l2.5-4h6l3 4h2q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T21 9.5v3h-.24");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ink232jbr {
  d: path("M5 14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.003-1.936q-.248-.064-.503-.064q-.095 0-.189.009t-.187.027t-.184.044t-.179.061t-.172.078t-.164.094t-.154.11t-.144.123t-.131.136q-.063.071-.118.148t-.103.158q-.048.082-.088.168q-.04.085-.072.175t-.054.181q-.024.091-.038.185t-.02.188M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

</style>
