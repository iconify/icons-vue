<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsuutoowp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:member-benefits" /></template>
<style>
.xsuutoowp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.4 10.5H3v-4h16v3.8m-14.5.2v9q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T6 21h6.779M11 6.5v7.6m0 2.9v4m0-14.5c-1.5-3.5-5-3-3.5 0m3.5 0c1.5-3.5 5-3 3.5 0m3.25 7.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
