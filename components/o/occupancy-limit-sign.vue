<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uelfr323z"/><path class="bjt2cxweb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:occupancy-limit-sign" /></template>
<style>
.bjt2cxweb {
  d: path("M12.243 21.5H6.5q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T5 20V6q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T6.5 4.5h6q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T14 6v5.779M11.75 13h.01m8.056 1.013l1.421 1.421a1.5 1.5 0 0 1 .439 1.061v2.01a1.5 1.5 0 0 1-.439 1.061l-1.421 1.421a1.5 1.5 0 0 1-1.061.439h-2.01a1.5 1.5 0 0 1-1.061-.439l-1.421-1.421a1.5 1.5 0 0 1-.439-1.061v-2.01a1.5 1.5 0 0 1 .439-1.061l1.421-1.421a1.5 1.5 0 0 1 1.061-.439h2.01a1.5 1.5 0 0 1 1.061.439M17.75 15.75v3.5m-1-2.75l1-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uelfr323z {
  d: path("M3 21.5v-19h13v8.3M2.5 21.5H12");
}

</style>
