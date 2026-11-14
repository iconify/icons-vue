<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z6hx9tb5l"/><path class="ozw89zaoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thermostat-up" /></template>
<style>
.ozw89zaoc {
  d: path("M7 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4-4v2.5M18 21v-6.5m-2.75 2.75L18 14.5l2.75 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6hx9tb5l {
  d: path("M13.543 19.5H4q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T2.5 18V4q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 2.5h14q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142t.022.146T19.5 4v7.679");
}

</style>
