<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wraenqwyg"/><path class="m4fz11bkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:me-time" /></template>
<style>
.m4fz11bkv {
  d: path("M12.685 18.5H2.5V13q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 11.5t.147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076t.119.087t.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T5.5 13v2.5h7.157m2.843-2.257V13q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076q.065-.035.133-.063t.139-.049q.07-.022.142-.036q.073-.015.146-.022T17 11.5t.147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T18.5 13v.215M4.5 18.5v2m11-4.5H20v3.25a2.25 2.25 0 0 1-2.25 2.25a2.25 2.25 0 0 1-2.25-2.25Zm4.5 1a1.5 1.5 0 0 1 0 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wraenqwyg {
  d: path("M5.5 13V6.5A2.5 2.5 0 0 1 8 4h5a2.5 2.5 0 0 1 2.5 2.5V13");
}

</style>
