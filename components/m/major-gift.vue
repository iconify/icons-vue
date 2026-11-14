<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0-05ywzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:major-gift" /></template>
<style>
.f0-05ywzt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 8h13.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 18.75 12H5.25a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 5.25 8M5 12v7.5q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T6.5 21h6.279M19 13.143V12m-7-4c-1-3.5-5-5.5-5-2.5C7 7 9 8 12 8s5-1 5-2.5c0-3-4-1-5 2.5m0 4v9m3.25-1.75v-2.171a.499.499 0 0 1 .875-.329a.927.927 0 0 0 1.511-.167l.114-.208a.854.854 0 0 1 1.5 0l.114.208a.927.927 0 0 0 1.511.167a.499.499 0 0 1 .875.329v2.171a1.5 1.5 0 0 1-1.5 1.5h-3.5a1.5 1.5 0 0 1-1.5-1.5");
}

</style>
