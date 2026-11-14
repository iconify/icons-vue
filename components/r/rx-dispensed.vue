<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nssp8jkib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rx-dispensed" /></template>
<style>
.nssp8jkib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.5h8.5A1.75 1.75 0 0 1 16 4.25v.5a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 4 4.75v-.5A1.75 1.75 0 0 1 5.75 2.5M5 6.5v13q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T6.5 21h7q.145 0 .287-.028M15 15.243V6.5M8 11h4m-4 4h2.5m4.25 3l2 2L21 15.75");
}

</style>
