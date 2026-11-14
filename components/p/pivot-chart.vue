<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0dyp8y7d"/><path class="sj49h3jjp"/><path class="gg0qdrbwg"/><path class="mti0imbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pivot-chart" /></template>
<style>
.gg0qdrbwg {
  d: path("M15.25 21.5V19a3 3 0 0 1 3-3h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mti0imbma {
  d: path("M19.5 14.25L21.25 16l-1.75 1.75");
}

.n0dyp8y7d {
  d: path("M3.5 3v17.5h8.9m5.7 0h1.3m.2 0H21");
}

.sj49h3jjp {
  fill: currentColor;
  d: path("M8 10.5zA1.5 1.5 0 0 1 9.5 12v4A1.5 1.5 0 0 1 8 17.5A1.5 1.5 0 0 1 6.5 16v-4A1.5 1.5 0 0 1 8 10.5m4.63 6.954q-.12-.031-.234-.081t-.218-.118t-.195-.152t-.167-.182q-.077-.098-.136-.208t-.099-.226q-.04-.118-.061-.24q-.02-.123-.02-.247V6.5q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119t.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T13 5t.147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146t.007.147v8.079");
}

</style>
