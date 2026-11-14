<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p8o7a7gou"/><path class="z4xgu_bwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:outdoor-sofa" /></template>
<style>
.p8o7a7gou {
  d: path("M15.685 14H2.5v-4q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 8.5t.147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076t.119.087t.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T5.5 10v1h9v-1q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049q.07-.022.142-.036q.073-.015.146-.022T16 8.5t.147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T17.5 10v3.015");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4xgu_bwp {
  d: path("M5.5 10V6a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v4M10 4v7m6.5 7.25a2.75 2.75 0 0 1 5.5 0Zm2.75 0v3.25");
}

</style>
