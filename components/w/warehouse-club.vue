<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hilek7b9u"/><path class="acdvalafg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warehouse-club" /></template>
<style>
.acdvalafg {
  d: path("M11.366 21.225q-.19.134-.412.205t-.454.07h-4q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T5 20v-5q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T6.5 13.5h4q.12 0 .238.019t.232.057t.22.092t.203.127q.096.071.18.156t.152.184q.069.098.122.205q.053.108.088.222M5 16h6.3M5 18.5h6.2m-2.7-8.25h7m.25 5h4.5A1.75 1.75 0 0 1 22 17v3a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 14 20v-3a1.75 1.75 0 0 1 1.75-1.75M14 17.5h8");
}

.hilek7b9u {
  d: path("M2.5 21.5V10C6 6 18 6 21.5 10v2.608");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
