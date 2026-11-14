<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tiyr0o_zj"/><path class="eza314bwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mushroom-check" /></template>
<style>
.eza314bwh {
  d: path("M7.5 11.25L7 19.5q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036t.146.022T8.5 21h2q.074 0 .147-.007t.146-.022t.142-.036q.071-.021.139-.049t.133-.063t.126-.076q.062-.041.119-.087q.057-.047.109-.099t.099-.109q.046-.057.087-.119t.076-.126q.035-.065.063-.133t.049-.139q.022-.07.036-.142q.015-.073.022-.146T12 19.5l-.018-.292m-.139-2.295L11.5 11.25M14.75 18l2 2L21 15.75");
}

.tiyr0o_zj {
  d: path("M2.5 12c0-5.5 4-9 9.5-9s9.5 3.5 9.5 9C18 10.75 6 10.75 2.5 12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
